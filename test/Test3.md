# Link rendering test

**1.  Test link without '/' in same folder path:**

[link](img/SystemAccount.png)

**2.  Test link with '/' relative path**

[link](/test/img/SystemAccount.png)

**3.  Test link with './' relative path**

[link](./img/SystemAccount.png)

**4.  Test link with '../' relative path**

[link](../test/img/SystemAccount.png)

**5.  Test link with 'https' absolute path**

[link](https://www.valcre.in/wp-content/uploads/2022/06/sap-erp-modules.jpg)

**5.  Test link with multiple type links in one line**

To test the ESPM application, [Postman REST Client](https://www.getpostman.com/apps) can be used. A Postman collection which is provided [here](../test/img/SystemAccount.png) has all the request URLs and sample request body payloads (in case of a POST request).
