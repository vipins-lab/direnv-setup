# direnv-setup

```txt
Vipins-MacBook-Pro:direnv-setup vipin$ direnv allow .
direnv: error .envrc file not found

touch .envrc

layout python3
export foo=bar


direnv allow .

--------------------------------------------------------------------------------------------

  687  cd direnv-setup/
  688  direnv allow .
  692  which python
  695  cd direnv-setup/

    touch .envrc
    echo "layout python3" > .envrc
    echo "export foo=bar" >> .envrc


  696  direnv allow .
  699  which python3
  $ which python
    .direnv/python-3.9/bin/python
--------------------------------------------------------------------------------------------


```

https://direnv.net/

