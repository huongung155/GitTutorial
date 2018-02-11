- List all branches
Image Tutorial:
![alt text](http://res.cloudinary.com/dqagyeboj/image/upload/v1518312176/Opera_Snapshot_2018-02-11_041506_www.youtube.com_u3efdn.png)
- Add a branch
-1. `git checkout -b <branch name>`: to create new branch
-2. `git branch`: to check created branch name
Image Tutorial:
![alt text](http://res.cloudinary.com/dqagyeboj/image/upload/v1518312275/Opera_Snapshot_2018-02-11_051506_www.youtube_h4lzho.png)
- Change branches: Change the pointer from `feature1` to `master`
-1. `git checkout master`
Image Tutorial:
![alt text](http://res.cloudinary.com/dqagyeboj/image/upload/v1518312281/Opera_Snapshot_2018-02-11_061506_www.youtube_veipvt.png)
- Merge branch
-1. if Create file in branch `feature1`
-2. This file only apprears when you checkout `feature1` branch
Generally, this is our branch look like:
	   /------0
      /
0-----0---0
-3. Assume, on `feature1`, you already done with form and want to merge with `master` branch
-4. Assume, you are in `master` branch, `git merge feature1`
-5. Now, GPU nano/vim, just Control^X to exit
	   /--0
      /   |
0-----0---0---/---
- Remove branch
-1. Assume you are in `master` branch
-2. To remove `feature1`, `git branch -d feature1`
0-----0---0---/---