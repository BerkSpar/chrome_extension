## Usage
To use this project as a Chrome extension, follow the steps below:

1. Clone this project.

2. From the project directory, run:
```sh
flutter build web --web-renderer html --csp
```

3. Go to the following URL from Chrome browser:
```url
chrome://extensions
```

4. Enable the **Developer mode**.

5. Click **Load unpacked**. Select the `<project_dir>/build/web` folder.

This will install the extension to your Chrome browser and then you will be able to access the extension by clicking on the **extension icon**.