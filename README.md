# Packer required

## quickstart accordingly using the repo below
(https://github.com/wbthomason/packer.nvim)
sourc the packer file and run PackerSync

## setup permissions
sometimes the folder permissions will be set to root instead of user:
`~/.local/share/nvim/site/pack/packer/start/packer.nvim`

chown to change the ownership back to the user

### example
`sudo chown -R (my username) pack`
