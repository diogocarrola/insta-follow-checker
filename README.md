# Instagram Follower Checker

A simple tool to check which Instagram users do not follow you back.

## How to Use

### Step 0: Download Your Instagram Data

1. Go to your Instagram profile and click on the **Settings** icon.
2. Select **Privacy and Security**.
3. Scroll down to **Data Download** and click **Request Download**.
4. Enter your email address and select **JSON** format.
5. Click **Next** and enter your Instagram password.
6. You will receive an email with a link to download your data. Click the link and download the ZIP file.

![Download Instagram Data](images/download-data.png)

### Step 1: Extract the Data Files

1. Unzip the downloaded ZIP file.
2. Ensure that the extracted folder contains the `followers.json` and `following.json` files.

![Extract Data Files](images/extract-data.png)

### Step 2: Use the Instagram Follower Checker

1. Open the [Instagram Follower Checker](https://diogocarrola.github.io/insta-follow-checker) in your browser.
2. Click on the **Choose Folder** button and select the folder containing the `followers.json` and `following.json` files.
3. Click the **Check** button.
4. The tool will display a list of users who are not following you back.

![Upload Data Files](images/upload-data.png)

## Development

To run this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/diogocarrola/insta-follow-checker.git
    cd insta-follow-checker
    ```

2. Open `index.html` in your browser.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
