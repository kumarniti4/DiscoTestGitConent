# Image tag rendering test

Test img tag without '/' in same folder path:

<img src="img/SystemAccount.png" width="500px" height="400px">

Test img tag with '/' relative path

<img src="/test/img/SystemAccount.png" width="500px" height="400px">

Test img tag with '../' relative path

<img src="../test/img/SystemAccount.png" width="500px" height="400px">

Test img tag with 'https' absolute path

<img src="https://www.valcre.in/wp-content/uploads/2022/06/sap-erp-modules.jpg" width="500px" height="400px">

Test img tag enclosed within [] (a href tag) - On clicking image, the image in github should open

[<img src="img/SystemAccount.png" width="600" />](img/SystemAccount.png)

