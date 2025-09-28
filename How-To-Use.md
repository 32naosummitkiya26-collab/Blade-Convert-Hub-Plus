# 📁 File Management
It's simple. There are no complicated functions.It's currently in alpha, so all you have to do is import files included in BCH+.<br>
You cannot upload files yourself (this is restricted due to insufficient disk space on the rental server).<br><br>
![1](https://github.com/user-attachments/assets/25e3dfe9-284c-4ca4-8560-f567539f1182)<br>
Currently you can import:
- Append
- MS-Copilot
- ChatGTP
- Startbootstrap-personal
- Constra-bootstrap-vsc
- Star-admin2
- Light-bootstrap-dashboard
- Bootstrap-dashboard-2.1.1-vsc
- Material-dashboard
- CoolAdmin-master

These 10 themes passed the test.<br><br>
In addition to the above, I have also downloaded Argon-dashboard-master, Awesome-dashboard, ChocoCake_template, Datta-lite, Ogani-master,
Pizza_template, Darkpan-1.0.0, Stream-dashboard, Portal-v3.0, Hybrid-admin, Sb-admin2, Bootstrap-admin-Codex,
Flat-able-lite, universal-3-0-2, and quixlab-bootstrap-main, but each of them has some kind of issue.<br><br>
I will test them one by one (I tested them a long time ago and haven't seen them since, so some may pass now) and add the ones that pass.

### Importing a File
Simply select a template from the dropdown menu and click the Import button.<br><br>
![2](https://github.com/user-attachments/assets/3cd4b511-ab0a-4f88-a4ab-d628481181d6)<br>
The following four operations are available for imported files:
- Move to Trash
- Restore from Trash
- Convert to Project
- Delete from Trash

The "Move to Trash/Restore from Trash/Delete from Trash" operations work the same as the Windows Recycle Bin.

### Change to Project
It's the same with bakeries, but no one does everything by themselves.
For example, roles are divided so that a designer creates the HTML templates and a programmer does the coding.<br>

If you simply import it, it will remain personal data. In other words, only you can see it.
If you change it to a project, you can share it with other team members. For example, a designer can upload an HTML file
and give access to it to a programmer. The programmer can convert it into a template, check the contents, and copy them if they're OK.<br><br>
![3](https://github.com/user-attachments/assets/e1cd5d54-f572-4c3c-b29a-95b259545b0c)<br>
The folder name will be "Original folder name PRJ-Email address". For example, Append PRJ-kai999@xxxx.xxx.<br><br>
Since project members know each other's email addresses, I don't think there's any problem with displaying the administrator's email address.
Currently, it's not possible to preview the converted template, but if you could, you could give clients access rights and let them see the finished product.<br><br>
Files that have been converted into project files cannot be changed back to personal files.<br>
For information on controlling access rights, see User Management.

# 🔄 Convert
This is where it's most used.
### Select a folder and proceed with the analysis
Select the folder you want to convert from the dropdown and click the Get File Info button.
Then select a framework and proceed with Doctype Analysis, HTML Analysis, and Head Analysis.<br>
This dropdown lists your personal folders, projects for which you are an administrator, and projects for which you have been granted conversion permissions.<br><br>
![6](https://github.com/user-attachments/assets/a61df0dd-7e7d-434c-a8d7-d313ac1977c0)<br>
Up to this point, there shouldn't be any problems. The currently included templates have been tested, so there's no need to worry.<br>
You can check the results of each analysis in the message window on the right.
However, if the commonality rate in the Head analysis is extremely low, you should be careful. This may be because unrelated files or files with completely different structures have been mixed in. You can convert them as is, but this will increase the amount of source code output to the child view. If you don't need these files, it's best to remove them.


Once the Head analysis is complete, you can check the conversion results so far. It's still incomplete, though.
For example, in Laravel, you can see the conversion results by clicking the xxx.blade.php link, and you can check the original source code by clicking Orig.


Laravel assets are placed directly under the public directory and loaded using the asset() function, while Django assets are placed directly under the static directory and loaded using the {% static %} tag.<br><br>
***Users who have been granted copy permissions in user management will see a link to the conversion results, but users who do not have the permissions will not be able to see them.
This means they cannot view the results or copy and paste them.***
### body structure extraction
![7](https://github.com/user-attachments/assets/c7cb568c-4713-4bfe-ac7e-2969687c39c2)

### Convert to template
There are four options available:
- Header: Base/Sub
- Navbar: Base/Sub
- Sidebar: Sub/Child
- Footer: Base/Sub<br><br>
![2](https://github.com/user-attachments/assets/dcd8d6eb-bd53-49f6-8e01-d45bf4e0ec4c)<br>
Where to output each part. The shape of the finished template will change depending on this.<br>
Initially, I had it set in stone and only output the sidebar to the subview, but I thought that there might be cases where the style is dictated by the coding rules of a team or client, so I changed it to make it selectable.<br>
Please try out various things.<br><br>
The subview name is taken from the id or class. For example,
```html
<footer id="footer" class="footer">
```
Then footer.blade.php,
```html
<nav class="breadcrumbs">
```
Then use breadcrumbs.blade.php. Feel free to change it to make it easier to understand.<br><br>
***I apologize if the indentation is off. Some of the original indentation was off, so I re-indented it myself.
I think this is also one of the reasons for the slowness. In the future, I think it would be good to have the option to use the original/BCH+ indentation.
For things that just didn't work, I saved the source code after re-indenting it with the VSC formatter.***

### Reset analysis results
You can reset the conversion results and start over again. Changing the hierarchy level, automatic adjustment, tags used for extraction, and separation into sibviews
will change the resulting template, so you can try it out as many times as you like until you find one that suits your needs.<br><br>
***Putting a file in or out of the trash in File Management will also reset the results.
This is because the commonality rate and other factors change depending on the source code being compared.***


# 👥 User Management
Here you can register, change, or delete access rights for projects for which you are the administrator.
![4](https://github.com/user-attachments/assets/d451896e-1645-468b-bc79-0da0f1450dce)
### Select a project
Select a project from the dropdown menu and enter the recipient's username and email address. Of course, only BCH+ subscribers are eligible.
The following four permissions can be granted:

- Upload
- Convert
- Copy
- Preview (Nothing works at the moment)
![5](https://github.com/user-attachments/assets/55efbf45-8623-4d74-97bb-1bf726d693d2)

Selection is possible on a folder-by-folder basis, and detailed management of individual files is not possible.
### Upload permissions
Users with this permission can perform a range of operations in file management. This means they can upload new files to the project and delete files from the project.

They cannot add new files to templates imported from BCH+.
Since those are provided by the author, I consider that to be complete.
### Convert Permissions
Users with this permission can perform all operations in Convert. For more information, see Convert.
###Copy permission
Users with this permission can cut and paste the source code of converted templates. See Convert for details.
