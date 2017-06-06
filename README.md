
2. clone vào : Bitbucket -> vào repostory đó và get clone ở Title Overiview chọn SSH

3. git clone _repo_Path  
 -- Nếu(máy mới cài) ko có SSH key thì phải tạo SSH key trước  trong thư mục :
 C:users/tên_máy/.ssh/id_rsa.pub
 lấy đoạn mã SSH key đó ra ( dùng lệnh cat trong command line ) rồi paste vào bitbucket - settings tìm phần SSH key 
 
 - vào thư mục cần pull code về, trong cmdagõ git clone (mã git_clone_SSH)
 
 Sau khi chạy xong thì thu mục kéo code về sẽ có source và thao tác cụ thể..
 
 NV1  : nganq tạo branch và push code lên 
 ...  câu lệnh tạo 1 branch mới ...
 git checkout -b feature/nganq
 checkout sang branch staging / feature/nganq
  
  git add *  -->> push tất cả các file
  git commit -m "nga nq init code"
  git push orign feature/nganq 
  
  
  
  ... vào slack check xem đã có ai commit chưa
  
  checkout xong rồi sẽ pull code về máy...
  
  
  
  
  FIXX CONFLICT
  b1 git brach -m tenbrach moi
git checkout stagging
git pull origin stagging
git check out -b tên_branch_bị confilt 
git merge tên_branch-backup
0-- sửa ... 
xong


git add ....
git commit -m "ab"

git push origin tên-BRANCH_mới(tene đang đứng)  --force
  
 NV2 : sẽ clone source từ staging push từ NV1
   và thứ tự các bước tương tự như đối với NV1
