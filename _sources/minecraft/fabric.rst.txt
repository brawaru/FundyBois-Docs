Installing Fabric
=================

.. note:: This is a simplified and inaccurate description.

Fabric is a very lightweight mod loader for Minecraft. Unlike Forge it does
not provide centralised ecosystem and instead allows mod developers freedom
of choice and relies on the the integration between other mods, such as
official Fabric API.

Because of how light it is and usage of injections system, it allows mods and
loader to be updated much quicker to newest Minecraft versions, to the point
it actually supports newest snapshots.

Another good feature of Fabric is ability to check for mod incompatibilities
before actually running the game, so you don't have to wait just to see that
one of the mods requires another mod with specific version.

Not a lot mods work great with this system, and mods highly dependent on
Forge APIs might find a difficult time updating to Fabric and abandon
this idea altogether. Once again, Fabric is experimental and new, so
it does not have a lot to offer.

If all you want is a few client mods, Fabric is a great choice.

Installing
----------

1. Go to official Fabric `download page <https://fabricmc.net/use/>`_ and
   download version for your platform (for example, EXE for Windows).

2. Open the downloaded file.

3. Select Minecraft version for which you install Fabric.

4. Make sure ‘Select Install Location’ field contains right path to the game.

5. Click ‘Install’ and wait until ‘Successfully Installed’ message appears.

6. Restart your Minecraft launcher for the Fabric version to show up.

.. _fabric_install-mods:

Installing mods
---------------

To install any mod, do the following:

1. Download your mod. Make sure it supports your game version.

   If mod depends on any other mod you have to install it the same way.

2. Open Minecraft launcher.

3. Click ‘Installations’ tab and find your Fabric profile.

4. However over it and click folder icon button next to ‘Play’.

5. Open ``mods`` folder and drop your mod JAR in this folder.

6. Launch the game, you don't need to restart launcher.

.. note::
   Regurarly check for updates to mods you have installed as they may
   contain crash and security fixes, as well as introduce new features.

.. admonition:: For players of the SMP
   :class: warning

   If you plan on playing our on SMP server, install only client-side mods.

   Do not install mods that introduce unfair advantage over others, as
   these might get you banned from the server and Discord.

   For example, a minimap mod would be okay (only ones that do not disclose
   other players' locations), while mod for fence jumping or literally flying
   is not.

While CurseForge only allows you to use Forge mod loader, you can actually
use it to manage Fabric
