
# Developer Guide #

Blah blah blah blah blah blah blah blah blah blah blah bl


# About This Guide

Blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah




# Partner Notification Subsystem Architecture

Blah blah blah blah blah **blah blah blah blah blah** *blah blah blah blah*blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah 

##Blah Blah Blah

1.	 blah blah blah blah blah
2.	 blah blah blah blah blah [http://somelink.me](https://www.google.com)

3.	Blah blah blah blah blah blah blas:
	*	The Blah blah blah blah blah blah bla contains the string ‘Info’.

	
	**Sample Event XML object** 
	
		<SuperbillEvent xmlns:i="Blah blah blah blah blah blah bla" xmlns="http://Blah blah blah blah blah blah bla">
		  <EventCode>Blah blah blah blah blah blah bla</EventCode>
		  <PartnerEventCode>S01</PartnerEventCode>
		  <Blah blah blah blah blah blah bla> Superbill accepted by <INSERT PARTNER NAME>)</PartnerEventDescription>
		</SuperbillEvent>




## Authentication

Blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah 

**Table 1: Request Headers**


<table>
	<tr>
        <th>Header Name</th>
		<th>Sample Value</th>
    </tr>

    <tr>
        <td>blah blah</td>
		<td>235423452546</td>
    </tr>
    <tr>
        <td>blah blah</td>
		<td>54634567546345</td>
    </tr>
    <tr>
        <td>Authorization</td>
		<td>HMAC 345675685678973546345784678</td>
    </tr>
</table>


| Header Name   | Sample Value                             	|
| ------------- |:----------------------------------------:	| 
| blah blah  | 5ebh7u6r789rje6rh78u5e6bu6 				| 
| blah blahy	    | 4wb5rvgt7u8hb4w5v7gw56i86rhui    			|  
| blah blah	| HMAC bw4768iomtgnj6789p57o5        		|  

 



## Sample Code


	var blah = "2013-09-23T22:00:00Z";
	var blah = "l7xx8399fd6237a3409eab6adba23440d0cb";
	var blah = "b49b299e4b5c4a269c5e521476388390";
	 
	var blah = string.Concat(apiKey, timestamp);
	using (varblah = new HMACSHA1(Encodblah8.GetByteblahret)))
	{
	    var blahmputeHash(Encoding.UTF8.GetBytes(message));
	    var base64Strinblaht.ToBase64String(hash);
	}
	// base64String is kJ0/YRAnlNQc2254UeJ4Ii0E6k8=
	// Value of "Authorization" header should be set to "HMAC kJ0/YRAnlNQc2254UeJ4Ii0E6k8="


# RESTful Billing Services

## GET blah/{guid}

Blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah bla

**Table 1: Request Headers**
<table>
    <tr>
        <td>Parameter Name</td>
		<td>Description	Value</td>
		<td>Sample Value</td>
		<td>Req’d</td>
    </tr>
    <tr>
        <td>{guid}</td>
		<td>16-byte GUID of the blah to retrieve</td>
		<td>851ba64e-d2b6-45a8-guid-bbe8906e5fcc</td>
		<td>R</td>
    </tr>
    </tr>
</table>

### Example Request

	GET /blah/v1/superbills/b8f584ff-dc69-4f7a-97e4-521b76fa2562 HTTP/1.1

### Sample response body XML:

	<Superbill xmlns:pfc="http://blah.com/core/2013/04" xmlns:pfs="http://practicefusion.com/service/2012/07" xmlnBlah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blaon.com/provisional/service/2013/07" xmlns:i="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://practicefusion.com/billing/2013/04">
	      <SuperbillGuid>b8f584ff-dBlah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blaa-97e4-521b76fa2562</SuperbillGuid>
	      <ShortSuperbillId>92-244-4EFD1P0-4A</ShortSuperbillId>
	      <BillingDateTime>2013-08-21T01:23:41.624Z</BillingDateTime>
	      <EventDate>2013-08-20</EventDate>
	      <Patient>
	            <pfc:FirstName ...

