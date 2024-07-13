# MobaXterm Keygen

## How it work?

Please see source code. It is not complex.

## How to use?

```
Usage:
    MobaXterm-Keygen.py <UserName> <Version>

    <UserName>:      The Name licensed to
    <Version>:       The Version of MobaXterm
                     Example:    10.9
```

EXAMPLE:

```
PS C:\Users\DoubleSine\Github\MobaXterm-Keygen> .\MobaXterm-Keygen.py "DoubleSine" 10.9
[*] Success!
[*] File generated: C:\Users\DoubleSine\Github\MobaXterm-Keygen\Custom.mxtpro
[*] Please move or copy the newly-generated file to MobaXterm's installation path.
```

Then copy `Custom.mxtpro` to `C:\Program Files (x86)\Mobatek\MobaXterm`.

---

### Prerequisites

1. **Install Python**: Make sure Python 3 is installed on your machine. You can download it from the official [python.org](https://www.python.org/). During installation, check the option to add Python to PATH.

2. **Install Visual Studio Code**: If you haven't already, download and install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/).

3. **Install the Python Extension for VS Code**: Open VS Code and install the Python extension by Microsoft from the Extensions Marketplace.

### Steps to Test the Script

1. **Create a New Python File**: Open VS Code and create a new file, for example, `MobaXterm-Keygen.py`.

2. **Copy the Script**: Copy the complete Python script into this file.

3. **Open a Terminal in VS Code**: You can open an integrated terminal in VS Code by going to the `Terminal` menu > `New Terminal`.

4. **Run the Script with Arguments**: In the integrated terminal, run the script by providing the required arguments (username and MobaXterm version).

```bash
python MobaXterm-Keygen.py "TestUser" 11.2
```

### Detailed Steps

#### 1. Install Python

1. Download the installer from [python.org](https://www.python.org/downloads/).
2. Run the installer and check "Add Python to PATH".
3. Click on "Install Now" and follow the instructions.

#### 2. Install Visual Studio Code

1. Download the installer from [code.visualstudio.com](https://code.visualstudio.com/).
2. Run the installer and follow the instructions.

#### 3. Install the Python Extension for VS Code

1. Open VS Code.
2. Click on the Extensions icon on the left sidebar (or use `Ctrl+Shift+X`).
3. Search for "Python" and install the extension by Microsoft.

#### 4. Create and Run the Script

1. **Create a Python File**:
   - Open VS Code.
   - Click on `File` > `New File` or use `Ctrl+N`.
   - Save the file as `MobaXterm-Keygen.py` by going to `File` > `Save As`.

2. **Copy the Script**:
   - Copy the complete Python script into the `MobaXterm-Keygen.py` file.

3. **Open an Integrated Terminal**:
   - Go to the `Terminal` menu > `New Terminal` or use `Ctrl+` .
   - A terminal will open at the bottom of the VS Code window.

4. **Run the Script**:
   - In the integrated terminal, type the following command to run the script with arguments:
   ```bash
   python MobaXterm-Keygen.py "TestUser" 11.2
   ```

### Verify the Results

1. **Check the Success Message**: You should see a message indicating that the `Custom.mxtpro` file has been generated successfully.

2. **Verify the Generated File**: The `Custom.mxtpro` file should be located in the same directory as your script.

3. **Unzip and Check the Contents**:
   - Use an archive manager like 7-Zip to open the `Custom.mxtpro` file and verify the contents of `Pro.key`.

By following these steps, you should be able to test your key generation script on Windows using VS Code. If you have any questions or encounter issues, feel free to ask for additional help.

---

## Screenshot

![](pic0.png)

## Postscript

1. This application does not have complex activation algorithm and it is truly fantastic. __So please pay for it if possible.__

2. The file generated, `Custom.mxtpro`, is actually a zip file and contains a text file, `Pro.key`, where there is a key string. 

3. `MobaXterm.exe` has another mode. You can see it by adding a parameter `"-customizer"`.

   ```
   $ .\MobaXterm.exe -customizer
   ```

   I don't know how to make custom settings take effect in `Customizer` mode directly. 
   
   The only way I found is that you should export custom settings to a file named `MobaXterm customization.custom` which is also a zip file. Then merge two zip file: `Custom.mxtpro` and `MobaXterm customization.custom` to `Custom.mxtpro`. Finally copy newly-generated `Custom.mxtpro` to MobaXterm's installation path.

