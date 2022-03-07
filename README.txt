Code to write tests
=====================
3) App/Helpers/TeHelper.php method willExpireAt
4) App/Repository/UserRepository.php, method createOrUpdate


Good Things about code:
=========================
- Good use of inheritance, Functions like find, update and delete.
- Proper loging is done in the good in constructor


Bad things about Code:
======================

- Crud operations should be in controller
- Validate function is created in base but not used.
- Get translator function should be in helper function.
- There should be sub functions in createOrUpdate logics
- user type id should be constant file no from env