A full usage guide for beginners is in the works. For now, please refer to [the KoboldAI wiki](https://github.com/KoboldAI/KoboldAI-Client/wiki) and the [KoboldAI Discord](https://discord.gg/nQaMX6GHYf).

&nbsp;


**Installation: Windows**

1. Clone the URL of the Github repository (git clone https://github.com/ghostpad/ghostpad.git)

2. Open install_requirements.bat as administrator.

3. Choose the regular version of Transformers.

4. You will now be asked to choose the installation mode, we strongly recommend the Temporary B: drive option. This option eliminates most installation issues and also makes KoboldAI/Ghostpad portable. The B: drive will be gone after a reboot and will automatically be recreated each time you use Ghostpad.

5. The installation will now automatically install its requirements. Some stages may appear to freeze. Do not close the installer until it asks you to press a key. Before pressing a key to exit the installer, please check if any errors occurred. Most problems with the app crashing are related to installation/download errors.

6. Use play.bat to start KoboldAI.

&nbsp;

**Installation: Linux**

1. Clone the URL of the Github repository (git clone https://github.com/ghostpad/ghostpad.git)
2. AMD user? Make sure ROCm is installed.
Intel ARC user? Make sure OneAPI is installed.
3. Run play.sh if you use an Nvidia GPU or you want to use CPU only

Run play-rocm.sh if you use an AMD GPU supported by ROCm

Run play-ipex.sh if you use an Intel ARC GPU


