# AWS Amplify Package - aws-amplify-react

AWS Amplify is a JavaScript library for frontend and mobile developers building cloud-enabled applications. The library is a declarative interface across different categories of operations in order to make common tasks easier to add into your application. The default implementation works with Amazon Web Services (AWS) resources but is designed to be open and pluggable for usage with other cloud services that wish to provide an implementation or custom backends.

`aws-amplify-react` is one of the AWS Amplify library packages, provide building blocks for React App development. Documentation is available [here](https://github.com/aws/aws-amplify/blob/master/README.md)

=================

Now you can add value to signUp inputs like:
<code>

<Authenticator

           signUpConfig={{
           
                      signUpFields: [
                          {
                            label: 'Referral Id',
                             key: 'custom:referralId',
                             // required: true,
                             placeholder: 'xxxx',
                             displayOrder: 3,
                             value: "24242"
                          },
                      ],
                      
           }}
>
</code>
