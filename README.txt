---------- Snap of Apache -----------

Commands to create the snap:

1) Move to the snap directory where the snapcraft.yaml is
2) execute "snapcraft --debug" (the --debug flag will open the snap filesystem if it fails to build)
3) install the snap "snap install --dangerous snap_name --classic"

4) run "snap run snapone.apache" to check is the apache daemon starts.


If you want to rerun after an installation the new build 

1) snap remove snap_name
2) move to the .yaml dir
3) snapcraft clean
4) snapcraft --debug

