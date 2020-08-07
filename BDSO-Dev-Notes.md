
## NUGET	

### References
* [Nuget.config reference](https://docs.microsoft.com/en-us/nuget/reference/nuget-config-file)
* [How to change where Nuget downloads packages](https://stackoverflow.com/questions/4092759/is-it-possible-to-change-the-location-of-packages-for-nuget)

### Nuget CLI Commands
Lists where Nuget stores downloaded packages when using PackageReference:
> `> dotnet nuget locals global-packages --list`

Clears package caches:
> `> dotnet nuget locals all --clear`

## GIT

## OpenSSL

Convert `.pfx` to `.pem` containing cert and private key:
>  \# winpty openssl pkcs12 -in filename.pfx -out cert.pem -nodes

\* [Why command needs `winpty`](https://omgdebugging.com/2019/03/17/openssl-hanging-up-when-trying-to-convert-certificates/#:~:text=OpenSSL%20Hanging%20Up%20When%20Trying%20to%20Convert%20Certificates%20on%20Windows,-This%20post%20is&text=This%20issue%20arises%20because%20in,winpty%20before%20the%20entire%20command.)
\* [Original reference](https://www.xolphin.com/support/Certificate_conversions/Convert_pfx_file_to_pem_file)

## .NET

* [Create self-signed certificates in .NET](https://stackoverflow.com/questions/48196350/generate-and-sign-certificate-request-using-pure-net-framework)

* [.NET implementation (libraries) of elliptic curve cryptography](https://stackoverflow.com/questions/690566/net-implementation-libraries-of-elliptic-curve-cryptography)

## Windows
* [Which process is locking a file/folder on Windows](https://superuser.com/questions/117902/find-out-which-process-is-locking-a-file-or-folder-in-windows)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAyNTk1NjE3OV19
-->