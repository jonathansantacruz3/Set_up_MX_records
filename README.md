![set up mx records](https://github.com/jonathansantacruz3/Set_up_MX_records/assets/151465848/35845204-6ef2-4d1a-aa7d-87d014b6dcd5)


<h1>Set up MX records on Hostinger</h1>
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

