# How to deploy
you need docker and maven installed, nothing else.<p>
sh Build.sh 
# Cloud-Rest-api
GET API CALLS<p>
<p>storage/mkdir - create new folder. Example
<p>cloud-service/storage/mkdir?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&directory=myfolder
<p>storage/rename - rename file or directory. Example 
<p>cloud-service/storage/rename?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&oldFilePath=myfolder&newFilePath=hisfolder
<p>storage/move - moves file or dir to another direcotry Example
<p>cloud-service/storage/move?key=a8b0de49-28ff-47cd-ad1e-<p>f24bed0056a4&sourceFile=hisfolder&new_file_name=hisfolder&destination=trash
<p>storage/search - search for files with given name
<p>cloud-service/storage/search?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=somename
<p>storage/remove - just removes file
<p>cloud-service/storage/remove?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=filename
<p>storage/restore_version - restores version of file with given name
<p>cloud-service/storage/restore_version?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=somefilename
<p>storage/restore - restores deleted file
<p>cloud-service/storage/restore?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=somefilename
<p>POST API CALLS
<p>/upload file have two parameters:
<p>target - path where to save file
<p>key - storage key(like a8b0de49-28ff-47cd-ad1e-f24bed0056a4)
