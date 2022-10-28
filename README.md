# How to Install Node.js (on my Corporate Windows Laptop)

1\. Go to the "Node.js" web site, <https://nodejs.org/>.

2\. Click on the "DOWNLOADS" tab, <https://nodejs.org/en/download/>.

3\. Then, click on "64-bit" of the line "Windows Binary (.zip)", <https://nodejs.org/dist/v18.12.0/node-v18.12.0-win-x64.zip>.

4\. Unzip the folder `node-v18.12.0-win-x64` into the folder `C:\Users\{Username}\AppData\Local\Programs`.

> ***Note:*** You may have to create the sub-folder `Programs` within the folder `C:\Users\{Username}\AppData\Local`.

5\. Open a _Command Prompt_ and type the following command:

```text
setx PATH "%PATH%;C:\Users\{Username}\AppData\Local\Programs\node-v18.12.0-win-x64`
```

6\. To verify the installtion, close the _Command Prompt_, open a new one, and type the following commands:

```text
node --version
```

```text
npm --version
```

> ***Note:*** At the time of writing these lines, I respectly get `18.12.0`  and `8.19.2` as versions.

## References

<https://nodejs.org/>

<https://code.visualstudio.com/docs/setup/windows>

<https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/setx>
