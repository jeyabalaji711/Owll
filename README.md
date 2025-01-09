_**OWLL** is a command-line tool designed to analyze AndroidManifest.xml files. It helps developers and security researchers identify potential vulnerabilities and misconfigurations in Android applications._

**Features**

Permission Analysis: Detects all permissions and highlights dangerous ones.

SDK Checks: Extracts and validates minSdkVersion and targetSdkVersion.

Exported Component Analysis: Flags exported activities, services, receivers, and providers.

Key Attribute Validation: Checks attributes like allowBackup, debuggable, and usesCleartextTraffic.

Detailed Summary: Provides a concise summary of findings.

**Installtion**

pip install owll

_(OR)_

git clone https://github.com/jeyabalaji711/Owll.git

cd Owll

python setup.py

owll

![image](https://github.com/user-attachments/assets/aa31b857-90b9-4407-af3a-7b9bce80d3df)

![image](https://github.com/user-attachments/assets/551d1491-1d9e-4b64-a80f-5bcb01ad1c42)

**Dependencies**

OWL requires the following Python packages:

colorama: For colorful CLI output.

These will be installed automatically when you install OWL via pip.

**Contributing**

We welcome contributions! Feel free to open issues or submit pull requests on our GitHub repository.

**License**

This project is licensed under the MIT License. See the LICENSE file for details.


