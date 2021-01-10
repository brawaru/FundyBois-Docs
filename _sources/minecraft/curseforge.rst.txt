Using CurseForge platform
=========================

CurseForge is known platform for downloading mods, but they also offer a
nice and easy-to-use solution for downloading and installing these mods.

If CurseForge is your primary source for mod downloads, you might want to
use their app to easily manage mods.

.. warning:: Java is required for CurseForge to be able to download mods.

.. warning:: Custom launchers are not supported by CurseForge.

Installing CurseForge
----------------------

.. warning:: You need administrator access to install CurseForge.

You can download CurseForge from `official site
<https://curseforge.overwolf.com/>`_.

Creating Custom Profiles
------------------------

1. Open CurseForge, select Minecraft on ‘Choose a Game’ screen.

2. Press :guilabel:`Create Custom Profile` button on top.

3. Enter meaningful profile name, select Minecraft and Forge version.

   By default latest version of Minecraft is selected with recommended
   Forge version.

4. Wait until it pre-installs everything.

5. Right click newly created profile and click :guilabel:`View Profile`.

6. Click :guilabel:`Add More Content`, type name of the mod and click
   :guilabel:`Install`.

7. When you finished click ::guilabel:`×` on top and click :guilabel:`Play`.

Playing mod packs
-----------------

After installing or creating a custom profile, click :guilabel:`Play` below it.

Clicking ‘Play’ will launch the official Minecraft launcher with working
directory set to CurseForge's one and your modpack profile selected.

Changes made from within this launcher window are not reflected on your
other Minecraft installations. This is also why you need to log in once
it starts.


.. _cf_profile-folder:

Adding own mods (profile folder)
--------------------------------

You can actually add your own mods like OptiFine: go to ‘My Modpacks’,
right click the needed pack, in context menu click :guilabel:`Open Folder`,
from there you can go to ``mods`` folder and drop downloaded mods' JARs.

Installing Fabric mods
----------------------

Even though CurseForge does not allow you to select Fabric version for
profile, you still can use it to create Fabric modpacks. To do so, you
need to use ‘Jumploader’ mod.

.. warning:: Please read Jumploader mod explanation for important details.

Jumploader mod is a tricky solution that ‘hijacks’ loading process, so
instead of Forge, Fabric loads instead. It downloads latest version of
Fabric during start-up, so you don't have to intall it manually.

Using Jumploader does **not** give you ability to load Forge mods on Fabric.

`Jumploader page on CurseForge →
<https://www.curseforge.com/minecraft/mc-mods/jumploader>`_
