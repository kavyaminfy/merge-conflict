# Assignment 3: Branching Strategies & Merge Conflicts 

Deliverables: 

1)Link to GitHub repository with merged branches ✅

![Screenshot 2025-05-06 173413](https://github.com/user-attachments/assets/218ff10a-4239-4f26-961f-9c16868b57fa)




2)Screenshots showing the merge conflict and resolution process ✅

![Screenshot 2025-05-06 232714](https://github.com/user-attachments/assets/055c6357-cb97-4abd-a0a8-4553e2c00692)
![Screenshot 2025-05-06 232906](https://github.com/user-attachments/assets/8f85c184-3961-4206-9834-5b163b3941fa)
![Screenshot 2025-05-06 232942](https://github.com/user-attachments/assets/43ee0363-efed-4285-815a-afc6e00975d9)
![Screenshot 2025-05-06 233053](https://github.com/user-attachments/assets/5683ed51-e9b4-4beb-bfe8-e627efb40d47)

# Merge conflicts
![Screenshot 2025-05-06 233132](https://github.com/user-attachments/assets/fa9185f5-3ed7-4c95-95da-1f26078c2cc2)
![Screenshot 2025-05-06 233202](https://github.com/user-attachments/assets/d2aea5c3-4310-40c0-b5c1-2f6cd2fe75fd)

# Conflicts resloved
![Screenshot 2025-05-06 233336](https://github.com/user-attachments/assets/4814aee7-c789-436d-ae19-e4a9b65430e8)
![Screenshot 2025-05-06 233720](https://github.com/user-attachments/assets/1afc5b28-c151-4d1e-9152-505a8f89b129)



3)Brief explanation of how the conflict was resolved ✅

While working on this assignment, I created two feature branches—feature/update-styling and feature/add-content—both of which made changes to the same line in myfile.html. I first merged feature/update-styling into the main branch without any issues.

However, when I tried to merge feature/add-content into main, Git threw a merge conflict because both branches had modified the same line differently. Git couldn’t decide which version to keep, so it marked the conflict in the file using special markers.

I opened myfile.html, located the conflict section, and saw both versions of the line separated by <<<<<<<, =======, and >>>>>>>. I manually edited the content to combine both changes in a meaningful way, removed the conflict markers, and saved the file.

After that, I staged the resolved file using git add, committed the changes with a message explaining that the conflict was resolved, and pushed the final result to the remote repository. This completed the merge successfully and preserved the work from both branches.








