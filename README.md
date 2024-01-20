# Getting Started Room Documentation
**Author:** Thomas McLaughlin

## Part 1
This guide will walk you through the initial steps to complete the "Getting Started" room. Begin by accessing the room at [TryHackMe](https://tryhackme.com/room/gettingstarted) and logging in.

### Step 1: Start the Lab
1. After logging in, you will see the main screen.
2. To begin, click on the **Task 1** drop-down menu.
3. Click the **Start Machine** button in the Task 1 menu.
4. In the popup, select "Attack box" to boot up the VM for the social media site attack.

    ![Start Machine Button](image-link-here) *Image: Start Machine button*

### Step 2: Access the Site
1. Once your machine is ready, open Firefox.
2. Navigate to the IP Address displayed on the top of your screen (e.g., `10.10.180.116`).

    ![Site Access](image-link-here) *Image: Accessing the IP Address*

### Step 3: Inspect HTML for Admin Pages
1. Inspect the HTML code of the site to find any hidden admin pages.
2. If found, use the path (e.g., `test-admin`) as your first flag.

### Step 4: Access Admin Page
1. In the URL, add the admin page path found earlier.
2. Your URL should now look like: `http://10.10.180.116/test-admin`.

    ![Admin Page](image-link-here) *Image: Accessing Admin Page*

### Step 5: Default Admin Credentials
1. Attempt to login using common admin credentials.
2. For instance, the username and password `admin:admin` might work.
3. Upon successful login, note down the two flags: admin credentials and the number of users.

    ![Admin Portal](image-link-here) *Image: Admin Portal after login*

### Completion
Finally, proceed to task 3 and submit a dummy answer to complete the room. Your screen should display a completion message.

---

Congratulations on completing the "Getting Started" room! This tutorial provided a practical example of a simple infiltration into an admin page.

