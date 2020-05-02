WHAT IS IAM ROLES:IT IS AN IDENTITY WHICH HAS SEVERAL RULES FOR RESTRICTION AND AUTHORIZATION .
                 :An IAM role is an IAM identity that you can create in your account that has specific permissions.


IAM ROLES NEED:
IN AWS ALL THE INTERIOR SERVICES CANNOT COMMUNICATE WITHIN EACH OTHER, FOR EG- EC2 TO S3 COMMUNICATION
IS NOT POSSIBLE. SO TO CREATE A COMMUNICATION BETWEEN THEM IAM ROLES ARE USED.

(aws s3 ls: list all avaiable s3.)

STEPS TO CREATE IAM ROLE FOR COMMUNICATION BETWEEN EC2 AND S3.
 -> search IAM from services (you will not have authorization)
 -> on left hand side window click on ROLES.
 ->click on create IAM role it will ask for which service you want to create an IAM role, so select EC2.
   (you can select multiple but in our case Ec2).
 ->NEXT:PERMISSION--there will be list of policies and you can create also. so select the
         appropriate policy --S3FULLACCESS.
 ->NEXT:TAGS--optional to give tags or not.
 ->NEXT:REVIEW-- ROLE NAME-give any
                 ROLE DESC-any.

  ->CREATE ROLE-- role will get created.



  HOW TO ATTACH ROLE IN EC2:
  -> FROM RUNNING INSTANCES SELECT EC2 ACTION -> INSTANCE SETTING->
      ATTACH/REPLACE IAMROLE  and select your created IAMROLE and 
      click on apply -> it will show IAMROLE applied.


      NOW USING EC2 YOU CAN COMMUNICATE WITH S3.                            
