![IPFS](https://ipfs.io/ipfs/QmZkNPfhoZnvHfEvaeMk6FFXUbZXbNGqEt4VH57QA7Yj4J)

Another fun project using IPFS. Simply uses wget mirror and IPFS to clone a URL and outputs an IPFS url endpoint.

Sample Clone URL link: https://ipfs.io/ipfs/QmdaA5vdEVHcyhGRueoMjcxeWXzDCMCN7LAnXy9hjgFx2P


# Setup on Ubuntu
Currently no installer so steps need to be taken manually.

1. Install [IPFS](https://ipfs.io/docs/install/)
2. install xclip, `apt-get install xclip`
3. Clone repository, `git clone git@github.com:uptownhr/ipfs-screenshot`
4. Start ipfs daemon, `ipfs daemon`

# Setup on Mac OS

1. Install [IPFS](https://ipfs.io/docs/install/)
2. Clone repository, `git clone git@github.com:uptownhr/ipfs-screenshot`
3. Start ipfs daemon, `ipfs daemon`

# Use Case
1. git clone git@github.com:uptownhr/ipfs-url-clone
2. cd ipfs-url-clone
3. ./webfs.sh http://some-url.com
4. go to outputed url
