# 通过git将项目上传到github
## 1、在github上创建一个仓库
### 上传01_testOpencv
\> `cd d:` <br>
\> `cd 01_testOpencv` <br>
\> `git init`                             //将项目变成一个git可以管理的仓库 <br>
\> `git add .`                            //告诉git，把该项目下的文件添加到仓库 <br>
\> `git commit -m "xxx"`                  //把文件提交到仓库，‘xxx’本次提交的说明 <br>
                                        //如果出现输入用户名和邮箱，则需要输入用户名和邮箱 <br>
                                        //git config --global user.emal "xxx@xx.com" <br>
                                        //git config --global suer.name "xxx" <br>
\> `git remote add origin` 自己仓库地址    //该地址在GitHub上对应仓库的HTTPS SSH后 <br>
\> `git push -u origin master`            //将文件上传到GitHub上 <br>
