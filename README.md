# Cloud-Rest-api
GET API CALLS
storage/mkdir - create new folder. Example
cloud-service/storage/mkdir?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&directory=myfolder
storage/rename - rename file or directory. Example 
cloud-service/storage/rename?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&oldFilePath=myfolder&newFilePath=hisfolder
storage/move - moves file or dir to another direcotry Example
cloud-service/storage/move?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&sourceFile=hisfolder&new_file_name=hisfolder&destination=trash
storage/search - search for files with given name
cloud-service/storage/search?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=somename
storage/remove - just removes file
cloud-service/storage/remove?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=filename
storage/restore_version - restores version of file with given name
cloud-service/storage/restore_version?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=somefilename
storage/restore - restores deleted file
cloud-service/storage/restore?key=a8b0de49-28ff-47cd-ad1e-f24bed0056a4&file=somefilename
POST API CALLS
/upload file have two parameters:
target - path where to save file
key - storage key(like a8b0de49-28ff-47cd-ad1e-f24bed0056a4)
