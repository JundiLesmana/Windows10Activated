### Method 1 - PowerShell (Windows 8 and later)

1.   Open PowerShell (Not CMD). To do that, right-click on the Windows start menu and select PowerShell or Terminal.
2.   Copy and paste the code below and press enter  
```
irm https://get.activated.win | iex
```
3.   You will see the activation options. Choose (1) HWID for Windows activation. Choose (2) Ohook for Office activation.
4.   That's all.

<details>
  <summary>More options</summary>

- Alternatively, you can use the following (It will be deprecated in the future.)
```
irm https://massgrave.dev/get | iex
```
- The URL `get.activated.win` might be blocked by some DNS services because it is a new domain.

</details>

---

### Method 2 - Traditional (Windows 7 and later)

<details>
  <summary>Click here for info</summary>

1.   Download the file using the links provided below.  
`https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip`  
or  
`https://git.activated.win/massgrave/Microsoft-Activation-Scripts/archive/master.zip`
2.   Right-click on the downloaded zip file and extract
3.   In the extracted folder, find the folder named `All-In-One-Version`
4.   Run the file named `MAS_AIO.cmd`
5.   You will see the activation options, follow the on-screen instructions.
6.   That's all.

</details>

---

> [!NOTE]
>
> - The IRM command in PowerShell downloads a script from a specified URL, and the IEX command executes it.
> - Always double-check the URL before executing the command and verify the source if manually downloading files.
> - Be cautious, as some spread malware disguised as MAS by using different URLs in the IRM command.

---
