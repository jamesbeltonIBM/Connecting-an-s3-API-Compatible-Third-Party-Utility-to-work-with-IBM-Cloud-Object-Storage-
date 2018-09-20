# Connecting-an-s3-API-Compatible-Third-Party-Utility-to-work-with-IBM-Cloud-Object-Storage-

If you’re a user of IBM Cloud Object Storage, you will know that there are two main ways that IBM provides to interact with your provisioned service – programmatically through the REST API and visually via the IBM Cloud console.

The IBM Cloud console is the easier of the two for most users, but it has certain limitations, such as a fundamental need for access to the console and a file size of 200MB.

Fortunately, the Cloud Object Storage API also supports the most common set of s3 API operations, which means that many s3 compatible tools, such as Cyberduck or Transmit as well as backup utilities such as Cloudberry and Duplicati can connect and be used. The advantage of this is that it gives users a much richer interface, the 200MB file size limit is removed and of course, there is no need to sign into IBM Cloud each time a user wants to upload or download an object. In the case of backup utilities, it offers a real alternative to tape and of course provides resilient, off site storage for backup files.

This guide provides step by step instructions on how to configure and use Transmit with Cloud Object Storage but in general, it provides the information you need to connect and use Cloud Object Storage with any third-party utility that is s3 compatible. 
