To change directory permissions for everyone, use “u” for users, “g” for group, “o” for others, and “ugo” or “a” (for all).
chmod ugo+rwx {foldername} to give read, write, and execute to everyone.
chmod a=r {foldername} to give only read permission for everyone.
chmod 007 {foldername} to give read, write, and execute permission to only the group owners.
chmod 004 {foldername} to give read permission to only the group owners.
chmod 002 {foldername} to give write permission to only the group owners.
chmod 001 {foldername} to give execute permission to only the group owners.
chmod 777 {foldername} to give read, write, and execute permission to everyone.
