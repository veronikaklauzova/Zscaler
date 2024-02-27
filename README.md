# Zscaler

### Postman Collection - Workflows - Use cases

#### ZIA
#### ZPA

##### App Connector Health Monitoring
1. Download Postman Collection Use Cases by cloning this full GitHub repository:

`git clone https://github.com/veronikaklauzova/Zscaler`

2. Open Postman application, then navigate to `File > Import` and drag and drop the required Postman collection use case file.

3. In Postman, create a new environment:

Navigate to `File > New > Environment`.
Enter the `name`of the environment (e.g., ZPA).
Add the following variables:
`customerId`: Enter your ZPA Tenant ID [(detailed instructions)](https://help.zscaler.com/zpa/configuring-company-profile).
`client_id`: This represents ZPA username details. Follow the steps to obtain this value.
`client_secret`: This represents ZPA password details. Follow the [steps](https://help.zscaler.com/zpa/about-api-keys) to obtain this value.
`token`: The value will be auto-populated with the authorization bearer access token, which will be passed down to subsequent API calls.

4. In Postman, from the top right corner drop-down menu, select the newly configured ZPA environment.

5. Expand the imported folder named "ZPA - App Connector Health Monitoring".

6. Click on the first API request "1. Login into ZPA Tenant" and hit the "Send" button - this will authenticate you into the ZPA tenant.

7. Select the second API request "2. Get All App Connector/s Health Status Details" and hit the "Send" button - in the body output, you can observe a list of all your configured App Connections from the ZPA Admin portal.

8. To logout from the ZPA Admin API portal, select the "3. Logout from ZP" API request and hit the "Send" button.


#### ZDX

### Postman Flows - Visualizations - Use case

#### ZIA
#### ZPA
#### ZDX
