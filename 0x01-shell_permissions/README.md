0-iam_betty : switches the current user to the user betty.
1-who_am-i : prints the effective username of the current user.
2-groups : prints all the groups the current user are part of.
3-new_owner : changes the owner of the file.
4-empty : creates an empty file.
5-execute : adds exe permission to the owner of the file.
6-multiple_permissions : adds exe permissions to the owner and grp owner, and read permission to other users.
7-everybody : adds exe permission to the owner, grp owner and the other users.
8-James_Bond : sets the permissions to the file.
9-John_Doe : sets the mode of the file.
10-mirror_permissions : sets the mode of the file hello the same as olleh's mode.
11-directories_permissions : adds exe permissions to all subdir of the current dir for the owner, the grp owner and all other user.
12-directory_permissions : creates a dir with permissions 751 in the working dir.
13-change_group : changes the grp owner.
100-change_owner_and_group : changes the owner to vincent and the grp owner to staff for all the files and dir in the working dir.
101-symbolic_link_permissions : changes the owner and the grp owner of _hello to vincent and staff respectively.
102-if_only : changes the owner of the file hello to betty only if it is owned by the user guillaume.
