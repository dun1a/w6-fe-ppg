
1. last monday's userController was shorter because the error catching logic was already in userSchema.static in the userModel. While in wednesday's code it's implemented in userController hence the longer length.

2.1 userSchema.statics.login in userModel.js is to specify that the following code is the logic for user login function.

2.2 "this" is used in userModel while "User" is used in controller.

2.3 bcrypt is imported in controller because the encryption logic is in the controller.

3. We both plan to use the logic in controller approach since we've already implemented the code in the controllers.


1. last monday's userController was shorter because the error catching logic was already in userSchema.static in the userModel. While in wednesday's code it's implemented in userController hence the longer length.

2.1 userSchema.statics.login in userModel.js is to specify that the following code is the logic for user login function.

2.2 "this" is used in userModel while "User" is used in controller.

2.3 validator is imported in controller because the validation logic is in the controller.

3. We both plan to use the logic in controller approach since we've already implemented the code in the controllers