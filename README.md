<p align="center">
  <img src="https://github.com/user-attachments/assets/bd4c09fd-cab4-4834-a7af-3e10c62309f3" alt="Screenshot 2025-07-03 211806" width="300" />
</p>

# Entra ID Bulk User Creation

## Platform and Tools Used

- Microsoft Entra ID
- Web browser
- CSV file

## Objective

In this project, I will demonstrate how to create new users in bulk in Microsoft Entra ID. Instead of creating users one by one, this method allows you to create many users at once. This approach is efficient and very useful for Entra ID administrators when working in big organizations where a large number of employees need to be added to the Microsoft ecosystem.

-----

## To Create Users in Bulk

1. Browse to **Users** > **Bulk Create**:
<img src="https://github.com/user-attachments/assets/24276bdb-0703-4c0c-b669-f08646af3601" alt="Screenshot 2025-06-30 200138" width="600" />

2. Click **Download**:

<img src="https://github.com/user-attachments/assets/d8e36cb6-86e8-4909-8f9a-addfbdbbebe9" alt="Screenshot 2025-06-30 200221" width="300" />

3. After I selected **Download**, I received a CSV file named **UserCreateTemplate**. I opened the file:

<img src="https://github.com/user-attachments/assets/4285aa60-dfc1-4d7b-ac29-ac831f2ebf97" alt="Screenshot 2025-06-30 200946" width="650" />

4. I followed the format in the template given to create new users. I added the required user information: **Name, User Principal Name, Initial Password, and Block Sign-In (Yes/No)**. Then saved the file:

<img src="https://github.com/user-attachments/assets/7cc6a93d-6b74-4be4-a6ca-7a4683671b3f" alt="Screenshot 2025-06-30 203944" width="650" />

5. On the **Bulk create user** page, under **Upload your CSV file**,  I clicked on the blue folder logo to locate and select my file. Once I selected the file and clicked **Submit**, the system begin validating the CSV file:

<img src="https://github.com/user-attachments/assets/0f4ba9c6-5f7b-43aa-a919-a5b4e0b3f122" alt="Screenshot 2025-06-30 201014" width="250" />

6. Once the file has been successfully uploaded, I navigated to the **Users** section and searched for the newly created users to verify they were all added successfully:

<img src="https://github.com/user-attachments/assets/a467b376-9d26-47ff-9cd0-6758a70cdfa1" alt="Screenshot 2025-06-30 204252" width="600" />

----

## Conclusion

This project demonstrated an efficient method to create users in bulk within Microsoft Entra ID, significantly reducing the time and effort compared to creating users individually. By leveraging the CSV template and bulk upload feature, administrators can easily manage large-scale user provisioning in enterprise environments. This approach ensures accuracy and consistency while simplifying user onboarding in the Microsoft ecosystem. Overall, bulk user creation is a valuable tool for IT professionals managing large organizations.
