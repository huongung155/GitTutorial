* List all branches
![alt text](https://9twp8g.ch.files.1drv.com/y4mEuyuFQY0-4rRmH1tGa8FlRv4raPBnDOTWxdZoJcPHdruC62tp_Q_LWhCKHg5ZyPwkK2ksjHw7xqmoIWrLyRFAdtG2hjVFMjLMF53xuSsbJD7GkcVdrnJf-aNkEEPq-akv8bHnpWQ365JKVhkamg6cIkLobRMlhURddgxOROQX64nfMu-HNhjBVmga5Pfpn02DHBBpVPpkQArulTUavxyeg/Opera_Snapshot_2018-02-11_061506_www.youtube_veipvt.png?psid=1)
* Add a branch
	* `git checkout -b <branch name>`: to create new branch
 	* `git branch`: to check created branch name
* ![alt text](http://res.cloudinary.com/dqagyeboj/image/upload/v1518312275/Opera_Snapshot_2018-02-11_051506_www.youtube_h4lzho.png)
* Change branches: Change the pointer from `feature1` to `master`
	* `git checkout master`
* ![alt text](http://res.cloudinary.com/dqagyeboj/image/upload/v1518312281/Opera_Snapshot_2018-02-11_061506_www.youtube_veipvt.png)
- Merge branch
* if Create file in branch `feature1`
* This file only apprears when you checkout `feature1` branch
* Generally, this is our branch look like:
```javascript
       /------0
      /
0-----0---0
```
* Assume, on `feature1`, you already done with form and want to merge with `master` branch
* Assume, you are in `master` branch, `git merge feature1`
* Now, GPU nano/vim, just `Control^X` to exit
```javascript
        /--0
       /   |
 0-----0---0---/---
 ```
- Remove branch
* Assume you are in `master` branch
* To remove `feature1`, `git branch -d feature1`
```javascript
0-----0---0---/---
```