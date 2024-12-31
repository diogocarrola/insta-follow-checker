# Instagram Follower Checker

A simple tool to check which Instagram users do not follow you back.

## How to Use

### Step 0: Download Your Instagram Data

1. Go to [Instagram Account Center](https://accountscenter.instagram.com/?theme=dark&entry_point=app_settings).
   ![Step 0.1](images/step0-1.png)
2. Select **Your Information and Permissions**.
   ![Step 0.2](images/step0-2.png)
3. Click on **Download Your Information**.
   ![Step 0.3](images/step0-3.png)
4. Select **Download or Transfer Information**, then **Some of Your Information**.
   ![Step 0.4](images/step0-4.png)
5. Scroll to **Connections** and select **All**.
   ![Step 0.5](images/step0-5.png)
6. Click **Next**, then **Download to Device**.
   ![Step 0.6](images/step0-6.png)
7. Ensure the format is set to **JSON** and select **Create Files**.
   ![Step 0.7](images/step0-7.png)
8. You will receive an email with a link to download your data. Click the link and download the ZIP file.
   ![Step 0.8](images/step0-8.png)

### Step 1: Extract the Data Files

1. Unzip the downloaded ZIP file.
   ![Extract Data Files](images/extract-data.png)
2. Ensure that the extracted folder contains the `followers.json` and `following.json` files.

### Step 2: Use the Instagram Follower Checker

1. Open the [Instagram Follower Checker](https://diogocarrola.github.io/insta-follow-checker) in your browser.
   ![Open Tool](images/open-tool.png)
2. Click on the **Choose Folder** button and select the folder containing the `followers.json` and `following.json` files.
   ![Upload Data Files](images/upload-data.png)
3. Click the **Check** button.
   ![Check Button](images/check-button.png)
4. The tool will display a list of users who are not following you back.
   ![Results](images/results.png)

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
