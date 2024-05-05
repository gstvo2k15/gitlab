### Original source --> https://gitlab.com/gitlab-org/omnibus-gitlab/-/tree/12.1.14+ee.0/docker

```
git clone https://gitlab.com/gitlab-org/omnibus-gitlab.git

docker-compose up -d

docker exec -it root-gitlab-1 grep Password: /etc/gitlab/initial_root_password
```


http://192.168.1.32/users/sign_in

root


Password: 
`hmPUgS9npRlMfsqWQV8nfie1PAABTAxZ/xG/p06Gstg=`

