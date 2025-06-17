# How to Submit an Internal Request in the Data Governance Tool

**Introduction to Internal Request**

An Internal Request is a pre-configured request submitted by an internal
team member on behalf of a customer. It is typically used when:

- A customer sends a request via email or another indirect channel.

- The internal team logs the request into the system using a predefined
  configuration (domain, requestor, act, request type).

- The request is flagged as internal and processed using an automated
  workflow.

This type of request is created through the DSA Request module in the
Data Governance Tool and can be reused or modified as needed.

**Introduction to DSAR**

Data Subject Access Requests (DSARs) are formal requests made by
individuals (data subjects) to access, manage, or delete their personal
data held by an organization.

Through DSARs, users can:

- Request a **copy or summary** of their personal data.

- **Opt-out** of data processing or **unsubscribe** from communications.

- **Delete** their personal data.

- And more, depending on the organization's configuration.

**Step by Step Guide to submitting a default internal request**

**1. Logging In**

Login to the Data Governance Tool by entering your credentials.

![](../../img/DSAR/Requests/Default_Internal_Request/image1.png)

**2. Navigating to DSA Request Module**

Click on the hamburger icon
![](../../img/DSAR/Requests/Default_Internal_Request/image2.png)

Click on 'DSA request' from the menu.

![](../../img/DSAR/Requests/Default_Internal_Request/image3.png)

**3. Setting Internal Request**

 In the DSA Request Module, turn on the toggle to "View Configuration"
option.

![](../../img/DSAR/Requests/Default_Internal_Request/image4.png)

- Navigate to "Mappings" Tab in View Configuration page.

- Click On Default Internal Request.

![](../../img/DSAR/Requests/Default_Internal_Request/image5.png)

- **Set Internal Request**:

We set up a **Default Internal Request** to streamline the submission process for internal users. This configuration ensures that users **do not have to manually select** the following fields each time they submit a request:

- **Domain**: Enter the domain.

- **Requestor**: Specify the requestor.

- **Act**: Select the relevant act.

- **Request Type**: Choose the request type.

<!-- -->

- **Save Configuration**: Click on the "Save" button to save your
  internal request settings.

> ![](../../img/DSAR/Requests/Default_Internal_Request/image6.png)

**4. Submitting the Request**

- **Switch to Active Requests**: Toggle from "View Configuration" to
"View Dashboard" to access active requests.

![](../../img/DSAR/Requests/Default_Internal_Request/image7.png)

> **Note:** The requests data and the filters visible to a user in DSA
> Request Dashboard are based on the tenant, acts, and requestors mapped
> to them in the user permissions mapping section.

- Click on the "+" icon to create a new request.

![](../../img/DSAR/Requests/Default_Internal_Request/image8.png)

**Open or Modify Request**:

- **Open**: Click "Open" to view the internal request you have saved.

- **Modify**: If needed, modify options like request type or act from
  the dropdown menu before opening.

![](../../img/DSAR/Requests/Default_Internal_Request/image9.png)

- **Navigate to Privacy Portal Request Form**: Clicking "Open" will
  navigate you to the privacy portal request form in a new tab.

- **Provide Details**: Fill in the required details in the privacy
  portal request form.

> ![](../../img/DSAR/Requests/Default_Internal_Request/image10.png)

- **Submit Request**: Click "Submit" to place your request.

![](../../img/DSAR/Requests/Default_Internal_Request/image11.png)

**5. Monitoring Request Status**

- **Refresh DGT or Check Active Requests**: After a few minutes of
  submitting the request, it will be displayed on top of the table.

![](../../img/DSAR/Requests/Default_Internal_Request/image12.png)

- **View Request Status**: Click on the status of your request to view
  details such as:

**Request ID**

<!-- -->

- A unique identifier automatically generated for each request.

- Used for tracking, referencing, and auditing purposes.

- Internal requests are by default treated as verified requests.

![](../../img/DSAR/Requests/Default_Internal_Request/image13.png)

**Status** (e.g., new, In Validation)

- Indicates the current stage of the request in the processing
  lifecycle.

**Automate**

- When checked, this indicates that the request is being processed using
  an automated workflow.

- Automation helps streamline internal handling and reduces manual
  effort.

**Internal Request** 

<!-- -->

- To identify whether the request is an internal request or normal
  request.

- An internal request is one that is submitted by an internal team
  member on behalf of a customer. This typically happens when a customer
  sends a request via email or another indirect channel.

![](../../img/DSAR/Requests/Default_Internal_Request/image14.png)

**Closed** 

- Indicates that the request has been completed or resolved.

**Disable Communication** 

- If checked(enabled): No external communication will be sent --- this
  is default for internal requests.

- If unchecked(disabled): External communication may be sent based on
  the request configuration.

- This setting allows flexibility for exceptions where communication is
  necessary.

**Submitted By**
-  Displays the email address of the person who
  submitted the request.

**NOTE: Do Not Reuse Old Request URLs**

- **Never use the URL from a previous request** to submit a new one.

- Reusing an old link will **bypass internal request logic** and treat
  it as a **normal request**.

![](../../img/DSAR/Requests/Default_Internal_Request/image15.png)