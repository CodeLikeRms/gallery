```cat photoR*.zip > whole.zip```

```zip -FF whole.zip --out photoRMS.zip```

```unzip photoRMS.zip```

Enjoy :)

# How zip a directory with command line and encrypted it ?

```zip -e -r <DEST>.zip <SOURCE_DIR>```

If your zip file is louder than 100MB you can upload it on github. Let see how 
by pass that:

We want to split our zip file in 50MB zip files (50 * 1024 * 1024 = 52428800 Bytes)

```zipsplit -n 52428800 <SOURCE>.zip```

Now you can push !

# How unzip a zipslit ?

```cat <SOURCE>*.zip > whole.zip```

```zip -FF whole.zip --out <VAR>.zip```

```unzip <VAR>.zip```
