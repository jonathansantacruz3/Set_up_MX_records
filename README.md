![set up mx records](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/35845204-6ef2-4d1a-aa7d-87d014b6dcd5)


<h1>Set up MX records and Create a Professional Email Account on Hostinger</h1>
This tutorial outlines the proper configurations of MX records on the Titan email service through the Hostinger. MX (Mail Exchange) records are part of the Domain Name System (DNS). They are text files that route e-mails to the appropriate mail servers used to handle incoming mail for a domain or its user. They specify which mail servers and protocols are used for mail reception, which are prioritized if there are more than one, and the TTL (time to live) for the record in the DNS cache. In other words, MX records are crucial for correct inbox routing and reliable email communication.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Edge Browser
- Hostinger platform
- Titan email service 

<h2>Operating Systems Used </h2>

- Windows 11</b> (23H2)

<h2>List of Prerequisites</h2>

- Internet connection
- Web hosting platform
- Email subscription
- Purchased Domain

<h2>Set Up Steps</h2>

Once logged in, navigate to the “Emails” tab in Hostinger. I use the Titan email service and I must locate what my domain uses for its name servers. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/aee684bf-85b1-4441-96c8-478244471841)





To locate the name servers, I will head over to the “Domains” tab, and under my desired domain I choose the "Manage" button. 
 
![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/11cf9f1a-8ab2-413a-8a69-2f9eb17f0765)
 
 
Then on the left panel choose the DNS/name server’s option. 
 
![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/bcbde9f7-1391-486b-9b9a-35da59276a54)
 
 
My domain uses Hostinger's DNS servers to handle e-mail communication. Therefore, I can make the configurations within the Hostinger platform. If they were non-Hostinger servers, those servers would handle the MX record settings. 
 
![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/b2943d8e-b617-400a-8bec-9d5b3574f73e)
 
 
The next step is to delete any pre-existing mx records to avoid any conflicting issues with the new records down the road. Then enter the following values into the fields for the appropriate mx and txt records. A txt (text) record is another method to prove domain ownership by adding a human-readable note associated with the domain and preventing domain spoofing. 

 
![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/1fb13d8c-9c77-428a-b8f5-79187258f938)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/b13a039f-8872-4f40-be80-33012a7db133)

 
The name @ will associate all mail to that desired domain and the priority level is what server takes precedence regarding email transmissions. The lower the number the higher the priority. They can both be set to the same number to distribute the load between an equal number of servers. TTL stands for time to live, and it is how long the DNS cache will store the data. The time is set to seconds so 14400 is set to 4 hours. Once the configuration is complete it can take up to 24 hours to process and validate.

<h3>Create An Email Account For Professional Use</h3>

Now that I have my mx record set up for my domain, it is time to create a professional email account tied to that domain. In Hostinger, head over to the "Emails" tab and choose the option "Email Accounts" and then "Create New Email Account" to create one. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/75a7b824-4cad-451e-a959-02899e98e4f8)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/9fcc606a-b0ef-47b0-8092-743969404fac)

In this window i will enter my desired fields to create a password and set a backup email account for password recovery. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/97d76729-ea84-4c79-b332-395a39dd92db)

After submitting the information and successfully creating a new account I was presented this window. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/b6ed67e4-d2ce-43e0-9d38-df754b1d27a2)

I decided to configure my new email address to assign it a signature to add a touch of professionalism. I navigated to titan.email and entered my brand new credentials. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/7f5c1867-caf6-4bde-9564-46e5facd6ecc)

I am greeted with an option to customize my account by adding a profile picture and a name to display for recipients. You can choose to set it now or skip and do it later. I decided to skip the picture for now.  

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/2b0bc3a6-4860-4be0-9832-53b292e4cdcf)

I am then asked to import my Gmail contacts, but I skipped it. The next window asked me to add a professional signature. I clicked on the "Create custom signature". 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/75af06d1-7d36-427c-bea5-8792b823c7bd)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/a3742c67-1f64-4c04-9d06-a69b2c4e9a50)

I entered my name, postion, and professional picture. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/f30132d0-f209-43c8-ae4a-5ecfe36bac48)

The next step is to configure email clients to Hostinger web and connect it to email hosting This way I will be able to manage all my emails under one roof. In Hostinger Emails tab, I opened the email settings and take note of the incoming and outgoing settings to apply them to the email client of your choice. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/253edab9-5847-48a4-8733-70bdea035782)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/142f5c27-c8a6-4711-a108-cff50fd5de26)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/d0aeca9d-7368-42c8-8c74-166a7130cc98)

I want to use Gmail to manage my emails so after I log in to my account, on the top right corner I choose the gear icon for settings and then the "see all settings" button. Then I head over to the "Accounts and Import" tab. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/f2ad06b0-045e-40ef-9310-c48dca206e8c)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/4993f054-6bdc-4976-9335-5af227c984eb)

Under "send email as:" choose to "Add another email".

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/d645ed60-1aeb-40b3-9904-458d05af2992)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/45292847-1266-4245-acf9-54606c35bbed)

Enter the SMTP hostname settings along with my domain credentials and protocol desired. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/3399e595-0761-4780-a3ff-2a9c089f390a)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/6f72abd4-62e5-489f-adc0-cbb924716302)

It prompts me to verify my new configuration by logging on to my Gmail account and confirming. 

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/d964cc7d-7584-4113-94bb-4f68f50c7cdd)

![image](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/abe1a2f5-6870-4728-b6d5-c8d9637e6c0b)

Success! I am now able to manage my email from one inbox. 
