# printclient-releases-dev
Contains releases for SimpleRfid print client for dev

Steps to deploy New print Client's version:
1. Increase Assembly vresion and File version of SimpleRfid.NewPrintClient project (these options will be in Properties -> Assembly Information window).
2. Increase SimpleRfid.NewPrintClient.Installer's Version (in Properties window). After increasing Version's number you'll see window which should ask you to change Product code. Press "Yes". (!IMPORTANT! SimpleRfid.NewPrintClient versions numbers and SimpleRfid.NewPrintClient.Installer version number should be the same).
3. Build SimpleRfid.NewPrintClient project in Dev or Debug mode.
4. Build SimpleRfid.NewPrintClient.Installer project in Dev or Debug mode.
5. Go to SimpleRfid.NewPrintClient.Installer's folder, then go into "Debug" folder, where you'll see simplerfid-printclient-dev.msi and setup.exe files.
6. Create new release with same number as your project's versions in this repository. And add simplerfid-printclient-dev.msi as attached file.
