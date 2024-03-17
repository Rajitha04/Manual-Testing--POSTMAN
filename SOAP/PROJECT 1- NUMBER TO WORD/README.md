#PROJECT 1:
This Project is about API testing with POSTMAN


Here we are going to test a SOAP API which converts number into words


URL:https://www.dataaccess.com/webservicesserver/NumberConversion.wso


#eg: payload = 500,  response = five hundred , response status = 200 OK

#Test cases:refer to NumbertoWords file for the list of executed test cases

BODY:
<?xml version="1.0" encoding="utf-8"?>


<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">


  <<soap:Body>>

  
    <NumberToWords xmlns="http://www.dataaccess.com/webservicesserver/">

    
      <ubiNum>500</ubiNum>

      
    </NumberToWords>

    
  </soap:Body>

  
</soap:Envelope>





