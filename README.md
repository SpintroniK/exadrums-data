# How to Install the TD-4KP kit

- Paste this code into a terminal:

```bash
wget https://github.com/SpintroniK/exadrums-data/archive/refs/heads/TD-4KP.zip &&
mkdir TD-4KP-temp &&
cd TD-4KP-temp &&
mv ../TD-4KP.zip . &&
unzip TD-4KP.zip &&
mkdir -p Data &&
cp -r exadrums-data-TD-4KP/* Data/ &&
rm TD-4KP.zip &&
zip -r TD-4KP.zip Data &&
cp TD-4KP.zip .. &&
cd .. &&
rm -rf TD-4KP-temp

```

- This will download and convert the `TD-4KP.zip` into an exadrums configuration file.
- Launch exadrums.
- Go to "Configuration" > "Import/Export", and choose "Import configuration from file".
- Select the `TD-4KP.zip` file and click `Yes`.
- The software restarts.

Have fun with the TD-4KP drum kit.
