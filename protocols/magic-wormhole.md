# Magic-Wormhole is a cool way to move data

The Magic-Wormhole protocol allows you to send encrypted data peer-2-peer across the internet. {{ more about magic-wormhole}}

 rrstickney on ice-station-zebra at …/Videos wormhole send files.tar.gz
Sending 23.3 GB file named 'files.tar.gz'
Wormhole code is: 88-applicant-tycoon
On the other computer, please run:

wormhole receive 88-applicant-tycoon

Sending (->relay:tcp:magic-wormhole-transit.debian.net:4001)..
100%|█████████████████████████████████████████████████████████████| 23.3G/23.3G [2:05:20<00:00, 3.10MB/s]
File sent.. waiting for confirmation
Confirmation received. Transfer complete.

 rrstickney on ice-station-zebra at …/Videos

ubuntu@ice-station-europa:~/Videos$ wormhole receive 88-applicant-tycoon
Receiving file (23.3 GB) into: files.tar.gz
ok? (Y/n): Y
Receiving (->relay:tcp:magic-wormhole-transit.debian.net:4001)..
100%|█████████████████████████████████████████████████████████████| 23.3G/23.3G [2:05:21<00:00, 3.10MB/s]
Received file written to files.tar.gz
ubuntu@ice-station-europa:~/Videos$

my upload speed from home kinda sucks

 rrstickney on ice-station-zebra at …/Videos wormhole receive 1-chambermaid-dashboard
Receiving file (23.3 GB) into: files.tar.gz
ok? (Y/n): Y
Receiving (->relay:tcp:magic-wormhole-transit.debian.net:4001)..
100%|███████████████████████████████████████████████████████████████| 23.3G/23.3G [36:07<00:00, 10.7MB/s]
Received file written to files.tar.gz

ubuntu@ice-station-europa:~/Videos$ wormhole send files.tar.gz
Sending 23.3 GB file named 'files.tar.gz'
Wormhole code is: 1-chambermaid-dashboard
On the other computer, please run:

wormhole receive 1-chambermaid-dashboard

Sending (->relay:tcp:magic-wormhole-transit.debian.net:4001)..
100%|███████████████████████████████████████████████████████████████| 23.3G/23.3G [36:07<00:00, 10.7MB/s]
File sent.. waiting for confirmation
Confirmation received. Transfer complete.
