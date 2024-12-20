
# Tarifit Keyboard for macOS  

The **Tarifit Keyboard** allows users to type in the Tarifit (Riffian) language seamlessly on macOS. This keyboard layout provides access to special characters commonly used in Tarifit, helping users write in their native script with ease. Whether you're an advanced user or someone new to custom keyboard layouts, this guide will walk you through the installation and usage process.  

## Installation  

### Advanced Users  
For advanced users, you need to clone the repository or directly download the zip file`Tarifit.bundle.zip` from [here](https://github.com/ipshel/TarifitKeyboardMacOS/raw/main/Tarifit.bundle.zip). Once you have the `Tarifit.bundle`, follow the steps below to copy it to the appropriate directory.

#### Option 1: Using Terminal (after cloning the repo)

1. **Clone the repository**:  
   Open Terminal and run the following command to clone the repository:
   ```bash
   git clone https://github.com/ipshel/TarifitKeyboardMacOS.git
   ```
2. **Navigate to the cloned repository**:
    Change to the directory where the `Tarifit.bundle` is located:
    ```bash
    cd TarifitKeyboardMacOS
    ```
3. **Copy `Tarifit.bundle` to the desired directory**:
    - **for local use**:
    ```bash
    cp -r Tarifit.bundle /Users/<yourname>/Library/Keyboard\\ Layouts/
    ```
    - **for system-wide use**:
    ```bash
    sudo cp -r Tarifit.bundle /Library/Keyboard\\ Layouts/
    ```
    
    In both cases, replace `<yourname>` with your username.

####  Option 2: Manual Copy

If you prefer to copy the file manually:
1. Downlaoad `Tarifit.bundle.zip` directly from [here](https://github.com/ipshel/TarifitKeyboardMacOS/raw/main/Tarifit.bundle.zip).
2. Extract the zip file in order to get `Tarifit.bundle`.
3. Open Finder and locate `Tarifit.bundle` file.
4. Manually copy `Tarifit.bundle` to one of the following directories:
    - For local use:
    `/Users/<yourname>/Library/Keyboard\ Layouts/`
    - For system-wide use:
    `/Library/Keyboard\ Layouts/`

    where `<yourname>` is your username.

### Regular Users  
Follow these steps to install the Tarifit Keyboard:  

1. **Download the disc image**
    You can download the `TarifitKeyboard.dmg` directly from [here](https://github.com/ipshel/TarifitKeyboardMacOS/raw/main/TarifitKeyboard.dmg)
2. **Open the downloaded image**  
   Double-click the `TarifitKeyboard.dmg` file.  
   ![screenshot](/screenshots/shot0001.jpg)  

3. **Install the keyboard**  
   Double-click the `Tarifit` Lego icon (red dot).  
   ![screenshot](/screenshots/shot0002.jpg)  

4. **Choose the installation option**  
   - Select **"Install for current user"** or **"Install for all users"**.  
   - Installing for all users will require authentication.  
   ![screenshot](/screenshots/shot0003.jpg)  

   ***If the above screen does not appear, proceed to Step 4. Otherwise, skip to Step 5.***  

5. **Alternative method (only if Step 3 fails)**  
   Drag the `Tarifit` Lego icon into the `Keyboard Layouts` folder (located in the right corner of the window). This method will require authentication.  
   ![screenshot](/screenshots/shot0004.jpg)  
   ![screenshot](/screenshots/shot0005.jpg)  

6. **Close the image**  
   Close the `Tarifit Keyboard` window.  
   ![screenshot](/screenshots/shot0006.jpg)  

7. **Eject the image**  
   Right-click and eject the `Tarifit Keyboard` image.  
   ![screenshot](/screenshots/shot0007.jpg)  

8. **Open Keyboard Preferences**  
   Go to System Preferences → Keyboard → Input Sources.  
   ![screenshot](/screenshots/shot0008.jpg)  

9. **Add the Tarifit Keyboard**  
   Click the **"+"** button and search for *Tarifit*, *Riffian*, or *rif*. Add the desired option.  
   ![screenshot](/screenshots/shot0009.jpg)  
   ![screenshot](/screenshots/shot0010.jpg)  

10. **Select Tarifit**  
   You can now select the Tarifit Keyboard as one of your input sources.  
   ![screenshot](/screenshots/shot0011.jpg)  

---

## Using Tarifit Keyboard  

You can access Tarifit characters using the `Option ⌥` key (or `Alt`) combined with or without the `Shift ⇧` key as shown below:  

| **Combination**          | **Character** |  
|---------------------------|---------------|  
| `⌥ + h`                  | ḥ             |  
| `⌥ + t`                  | ṭ             |  
| `⌥ + d`                  | ḍ             |  
| `⌥ + z`                  | ẓ             |  
| `⌥ + s`                  | ṣ             |  
| `⌥ + g`                  | ɣ             |  
| `⌥ + e`                  | ɛ             |  
| `⌥ + w`                  | ʷ             |  
| `⌥ + ⇧ + h`              | Ḥ             |  
| `⌥ + ⇧ + t`              | Ṭ             |  
| `⌥ + ⇧ + d`              | Ḍ             |  
| `⌥ + ⇧ + z`              | Ẓ             |  
| `⌥ + ⇧ + s`              | Ṣ             |  
| `⌥ + ⇧ + g`              | Ɣ             |  
| `⌥ + ⇧ + e`              | Ɛ             |  
| `⌥ + /`                  | ⵣ             |  

---

## Contributing  

This project is part of the [Open Rif Project](https://openrif.com).  
For more information or contribution please contact info@openrif.com.  

---

## License  
This project is licensed under the [GPL](LICENSE).  

**2020**  
