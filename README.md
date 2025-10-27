# Box JWT

***This plugin allows generating token from box, show list of files, upload files to box and download files from box.***


## Box JWT
| Item         |           Value           |
|--------------|:-------------------------:|
| Icon         | ![Plugin Name](icon.png)  |
| Display Name |        **Box JWT**        |

## Arun Kumar (ak080495@gmail.com)

Arun Kumar
* [email](mailto:ak080495@gmail.com) 
 
## Version Control 
* [4.913.1342](setup.yaml)
* Release Date: `September 13, 2022`


## Primary Features
Get the file/folder lists, upload and download the files from BOX

## Create credentials from Box console

1. Create apps in here: https://account.box.com/login?redirect_url=%2Fdevelopers%2Fconsole

![Box JWT Input Data](box%201.png)

# App Setup & Folder Collaboration — Step-by-step Guide

Follow these steps to create a custom app, configure JWT authentication, approve access, and grant folder collaboration.

---

## 1. Create custom app

![Create custom app](README_2.png)

---

## 2. Fill automation settings

![Fill automation settings](README_4.png)

---

## 3. Select **JWT Auth**

![Select JWT Auth](README_5.png)

---

## 4. Verify JWT auth

![Verify JWT Auth](README_6.png)

---

## 5. Add public key

When you add the public key, the system will download a `config.json` file for you.
![Add public key / download config.json](README_7.png)

---

## 6. Send approval request

Submit an approval request so the app can be enabled; you can disable it later if needed.
![Send approval request](README_8.png)

---

## 7. Open the Mage Console

![Open Mage Console](README_10.png)

---

## 8. Approve the app for access

Approve the pending request to grant the app access.

![Approve for access](README_13.png)

---

## 9. App approved — now active

Once approved, the app will be active.

![App approved and active](README_14.png)

---

## 10. Receive a separate email ID for collaboration

You will get a separate email address (account) to use when collaborating on folders.

![Collaborator email ID](README_15.png)

---

## 11. Open the folder and click **Share** to grant access

Open the folder you want to share and click **Share** to add collaborators.

![Open folder and click Share](README_18.png)

---

## 12. Access the granted folder and perform operations

After sharing, you (or collaborators) can access the folder and perform the allowed operations.
![Access granted folder](README_19.png)

---




## Input (Required)
| Display Name                 | Selection                           | Default Value          |
|------------------------------|-------------------------------------|------------------------|
| File/Folder Lists            | Config File                         | type,id,name           |
|                              | Folder ID                           |                        |
| Upload Files                 | Config File                         | name,id                |
|                              | Files to Upload                     |                        |
|                              | Folder ID                           |                        |
| Download Files/Folder        | Config File                         | (Downloaded file path) |
|                              | Folder ID or File ID                |                        |
|                              | Output Path                         |                        |
| Copy Files/Folder            | Config File                         | name,id                |
|                              | Additional Folder ID or/and File ID |                        |
|                              | Destination Folder ID               |                        |
| Move Files/Folder            | Config File                         | name,id                |
|                              | Additional Folder ID or/and File ID |                        |
|                              | Destination Folder ID               |                        |
| Delete Files/Folder          | Config File                         | id deleted.            |
|                              | Additional Folder ID or/and File ID |                        |
| Create or update Shared Link | Config File                         | id,link                |
|                              | Additional Folder ID or/and File ID |                        |
| Remove Shared Link           | Config File                         | id remove              |
|                              | Additional Folder ID or/and File ID |                        |


## Return Value

### Normal Case
Description of output result

## Return Code
| Code | Meaning                      |
|------|------------------------------|
| 0    | Success                      |
| 1    | Failure (Invalid Input Type) |
| 99   | Exceptional case             |

## Output Format
You may choose one of 3 output formats below,

<ul>
  <li>String (default)</li>
  <li>CSV</li>
  <li>File</li>
</ul>  


## Parameter setting examples (diagrams)

## Operations

### Get Access Token:

![Box JWT Input Data](README_Get%20Token%20Access.png)

### File/Folder Lists:

![Box JWT Input Data](README_Get%20file%20list.png)

### Upload Files:

![Box JWT Input Data](README_Upload%20file.png)

### Download Files/Folder:

![Box JWT Input Data](README_Download%20files.png)

### Copy Files/Folder:

![Box JWT Input Data](README_Copy.png)

### Move Files/Folder:

![Box JWT Input Data](README_Move.png)

### Delete Files/Folder:

![Box JWT Input Data](README_Delete.png)

### Shared_Link Files/Folder:

![Box JWT Input Data](README_Shared_Link.png)






