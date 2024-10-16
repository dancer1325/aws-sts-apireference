* AWS STS
  * 👁-- provided as -- web service / 👁
    * ️enable to request for users, credentials ️	
      * temporary
      * limited-privilege
  * ways to use the AWS STS API
    * directly 
    * through AWS SDKs
      * 👁SDKs -- provide a -- convenient way to create programmatic access to AWS STS👁
        * _Example:_ SDKs can cryptographically sign requests, manage errors, and retry requests automatically
  * endpoints
    * https://sts.amazonaws.com
      * 1! endpoint
        * Reason: 🧠by default, AWS STS is available as a global service 🧠
        * Global requests -- map to the -- US East (N. Virginia) Region
    * Regional AWS STS endpoints
      * vs previous global endpoint
        * 👁recommended to use regional ones 👁
          * Reason: 🧠 reduce latency, build in redundancy, and increase session token validity
      * check [Managing AWS STS | AWS Region](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp_enable-regions.html)
      * TODO:
        

* check 
  * [Temporary Security Credentials](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html)
  * [Signing AWS API Requests](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_sigv.html)
  * [Query API](https://docs.aws.amazon.com/IAM/latest/UserGuide/programming.html)
  * [using security tokens with other AWS products](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_aws-services-that-work-with-iam.html)