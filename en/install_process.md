# Install Process

There are a number of components to a successful OJS install: downloading and unpacking the OJS application files in a web accessible directory on your server; creating a separate files/ directory that is not web accessible; and most likely, manually creating a database user and database.

### Note
> All servers are different, and the installation process in your case may be different than what follows. If any of this confuses you or for some reason does not work, be sure to check the documentation that comes with OJS in the docs/ folder, as well as the support forum and FAQ. But also be sure to read your service provider and server documentation as well.



## Download and unpack OJS Installation File

All OJS downloads can be found at http://pkp.sfu.ca/ojs_download. Depending on your circumstances you will want to download either the most recent stable version (best for production systems) or the most recent development version (less stable but with more features). The install process is the same for both versions. In this example, we will use the development version, ojs-3.00.tar.gz.

Unpack the tar file, and move the unpacked contents to a web-accessible directory on your web server from which you want OJS to run. A common web-accessible directory is /var/www/html, which we will use for this example.

###Note
> Regarding web accessible directories: each server is different. If you do not know where your web-accessible directory is (that is, the directory where you put everything that you want people to see on your website; sometimes called a web root directory), you should contact your service provider.

If you did not download the tar file directly to your web server, you can untar the tar file on your desktop and transfer its contents by FTP, or you can transfer the tar file by FTP to your web server directly and run the following command: