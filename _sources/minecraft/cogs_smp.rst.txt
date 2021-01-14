TheCo(g)sSMP
============

This is an another of our SMPs, dedicated to mod Create.

Create is a fantastic technological (steampunk?) mod that adds lots of
machinery to the Minecraft world. Unlike regular mods, Create has a very
aesthetic feel to it — it's not just decorated blocks with custom
inventories.

Unlike our other SMP, this one is in hard mode and focused towards survival
aspect. It does not really mean it's hard, but certainly requires to adapt.
Cowardice, tactics and patience are your best friends in this world.

.. image:: assets/create_thumbnail.png
   :alt: Create YouTube trailer thumbnail.
   :target: https://youtu.be/jDIuWv7ROi8
   :align: center
   :scale: 65%

How to join
-----------

Installing the pack
^^^^^^^^^^^^^^^^^^^

In order to join the server you have to install mod pack with all required
mods. To do so, you can either use GDLauncher (recommended), CurseForge or
pre-packed version.

.. tabs::

   .. tab:: Via GDLauncher

      **Last Updated**: 11/01/2021.

      GDLauncher can be used as an alternative to CurseForge if you don't
      want to do anything with Overwolf, or couldn't install it by some
      reason (no administrator access).

      It will download the mod pack just like CurseForge would do, as well as
      it can manage Java for you. All that without administrator access and
      shady and bloated applications like Overwolf.

      .. note::
         To use Microsoft Account with GDLauncher, you have to download a
         beta version of it available `on GitHub
         <https://github.com/gorilla-devs/GDLauncher/releases>`_. Latest
         published version is on top, might be marked as ‘Pre-release’.

      1. `Download and install GDLauncher <https://gdevs.io/>`_.

      2. Download :download:`mod pack file </_static/created.zip>`
         (do not unpack!).

      3. Log in into your account and complete the introduction.

      4. Click :guilabel:`+` at the bottom left.

      5. In the popup window, select :guilabel:`Import Zip` tab.

      6. Select downloaded mod pack file and click :guilabel:`→`.

      7. (Optionally) You can change instance name if you want.

      8. Click :guilabel:`→` again. The mod pack will appear in instances list.

      9. Wait until it's downloaded (might take a while).

      10. Click on it to launch the game!

   .. tab:: Via CurseForge

      **Last Updated**: 11/01/2021.

      Installing a mod pack using CurseForge is easy and quick. Everything
      is written for you in a manifest file, all you need to do is import
      it in your CurseForge app and launch the game.

      .. rubric:: Importing mod pack in CurseForge:

      1. :doc:`Install CurseForge <curseforge>` normally.

      2. Download :download:`mod pack </_static/created.zip>` (do not unpack).

      3. Go to CurseForge, click :guilabel:`Create Custom Profile` on top.

      4. Click ‘import’ link in ‘Or **import** a previously created profile’

      5. Select downloaded mod pack file (``created.zip``) and click
         :guilabel:`Open`.

      6. Mod pack should immediately appear in your list.

      7. Click :guilabel:`Play` to launch the game!

   .. tab:: Pre-packed (TL/Minecraft)

      **Last Updated**: 11/01/2021.

      Pre-packed version is a portable version of Minecraft with all mods,
      Forge version profile pre-installed. It contains both Minecraft
      Launcher and TL executables that can be started using different
      shortcuts.

      Link to a recent version is available in pinned messages of ``#gaming``
      channel in Discord.

      .. rubric:: Launch via Minecraft Launcher:

      1. Start Minecraft Launcher using ``start_mc.bat`` file.

      2. Log in to your account.

      3. Make sure ‘Cogs SMP’ profile is selected.

      4. Click :guilabel:`Play` to launch the game!

      .. rubric:: Launch via TL:

      Official TL launcher available and can be used by players without
      official Mojang account. Ely.by accounts can be added, but skins
      loaded with it will be local and not visible to other players on
      the server.

      1. Start TL using ``start_tl.bat`` file.

      2. Add your profile (first combo box).

      3. Press :guilabel:`Enter the game` to launch the game!

Set Java arguments
^^^^^^^^^^^^^^^^^^

For better performance, use the following Java arguments (copy all lines!).

.. code-block:: text

   -Xmn768m -Xmx2G -Xms512M -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC
   -XX:+UseParNewGC -XX:+UseNUMA -XX:+CMSParallelRemarkEnabled
   -XX:MaxTenuringThreshold=15 -XX:MaxGCPauseMillis=30
   -XX:GCPauseIntervalMillis=150 -XX:+UseAdaptiveGCBoundary
   -XX:-UseGCOverheadLimit -XX:+UseBiasedLocking -XX:SurvivorRatio=8
   -XX:TargetSurvivorRatio=90 -XX:MaxTenuringThreshold=15
   -Dfml.ignorePatchDiscrepancies=true
   -Dfml.ignoreInvalidMinecraftCertificates=true
   -XX:+UseFastAccessorMethods -XX:+UseCompressedOops -XX:+OptimizeStringConcat
   -XX:+AggressiveOpts -XX:ReservedCodeCacheSize=2048m
   -XX:+UseCodeCacheFlushing -XX:SoftRefLRUPolicyMSPerMB=10000
   -XX:ParallelGCThreads=10

To set arguments, select way you installed mod pack:

.. tabs::

   .. tab:: Via GDLauncher

      1. Right click the pack in instances list.

      2. Select :guilabel:`Manage` in context menu.

      3. Toggle ‘Override Java’ to enabled state.

      4. Paste the copied arguments (using ``Ctrl`` + ``V``).

   .. tab:: Via CurseForge

      .. warning::
         **Arguments set globally.** If you plan on playing other packs,
         you'll have to clear ‘Additional Arguments’ field.

      1. Click |fa-gear| in the bottom left.

      2. In ‘Game Specific’ select Minecraft.

      3. Scroll down to ‘Java Settings’.

      4. Paste the copied arguments in ‘Additional Arguments’ field
         (using ``Ctrl`` + ``V``).

   .. tab:: Pre-packed (TL/Minecraft)

      .. image:: assets/tada-emoji.svg
         :class: tada-emoji
         :alt: Party popper emoji
         :align: left

      .. rubric:: Lucky You!

      Arguments are all set already :)

      .. raw:: html

         <style> .tada-emoji { height: 3em !important; }</style>
         <span class="clearfix"></span>

.. |fa-gear| raw:: html

   <i class="fa fa-cog"></i>

.. note::
   If your Minecraft freezes frequently, check out F3 and see if ‘Mem’ in
   top right corner reaches ~90% right when it freezes.
   
   If so, consider bumping ``-Xmx`` argument to ``2560MB`` or even ``3G``,
   it dictates how much RAM Minecraft can use.

Install OptiFine
^^^^^^^^^^^^^^^^

You can (and should!) install OptiFine to improve performance of the
game even more. OptiFine is being installed like a :ref:`normal Forge mod
<forge_install-mods>`.

**Please use version pre12 or latter for 1.16.4**. Preview versions are
hidden under ‘+ Preview versions’ spoiler. Pre12 added compatibility for
Forge 35.1.36, which we currently use for the pack.

.. rubric:: Options recommended to enable

- Performance → Render Regions: enable.
- Performance → Smart Animations: enable.
- Performance → Fast Render: enable.

- Details → Trees: Smart
- Details → Rain: Fast / disable.

Joining the server
^^^^^^^^^^^^^^^^^^

The IP, as always, can be found in pinned messages of ``#gaming`` Discord
channel.

Server features
---------------

Custom skins / capes
^^^^^^^^^^^^^^^^^^^^

/skin set <username / url>
""""""""""""""""""""""""""

Sets skin of the player.

:Arguments:
   * **username** – Username of player which skin to apply.
   * **url** – Link to skin file to apply.

/skin reset
"""""""""""

Reset the skin to default one.

.. warning::
   As our server is working in offline mode, skin will be reset to either
   Steve or Alex. To set skin to your own use ``/skin set <your nick>``.

/cape set <username / url>
""""""""""""""""""""""""""

Sets cape of the player.

.. warning:: This won't download OptiFine capes.

:Arguments:
   * **username** — Username of the player which cape to apply.
   * **url** — Link to cape file to apply.

/cape reset
"""""""""""

Resets cape of the player.

.. warning:: As with the skins, no cape will be present if reset.

/ftbteams create <name>
"""""""""""""""""""""""

Creates a team.

:Arguments:
   * **name** — Name of the team.

/ftbteams leave
"""""""""""""""

Leave your current team.

/ftbteams modify <property> <value>
"""""""""""""""""""""""""""""""""""

Modifies certain attributes of the current team.

:Arguments:
   * **property** — property to modify (use Tab for list).
   * **value** — value to set property to.

/ftbteams invite <player>
"""""""""""""""""""""""""

Invites player to your team.

Player joining the team must leave their current team.

:Arguments:
   * **player** — name of the player to invite.

Disabled mod features
---------------------

Quark
^^^^^

.. role:: del
   :class: del

* **Chute**. Use Chute from Create mod.
* **Iron Rod**. Use Drills from Create mod.
* **Endermites Form Shulkers**. Weird feature.
* **Greener Grass**. Too green.
* **Compasses Work Everywhere**. Cheat-y? Might be re-enabled.
* **Sign Edit Requires Empty Hand** enabled. Can imagine it being annoying.
* **Chorus Vegetation**.
* **Enchanted Ladders**. Cause of random weirdness when climbing ladders.

Change log
----------

1.0.3-BETA
^^^^^^^^^^

:Added:
   - **Quark Oddities**: meta mod to enable quark oddities addon.

1.0.2-BETA
^^^^^^^^^^

:Updated:
   - **Quark**: fixes crash.
   - **Create**: fixes and improvements.
   - **Jade**.
   - **Biomes O' Plenty**: language files updates.
   - **Chisel & Bits**: fixes memory leak and performance issues.
   - **Just Enough Resources**: fixes broken overall trades view.
   - **Decorative Blocks**: fixes server crash.
:Changed:
   - **Quark**: disabled ‘Enchanted Ladders’ tweak due to bugs.

1.0.1-BETA
^^^^^^^^^^

:Updated:
   - **Quark** to the newest version.
:Changed:
   - **Pre-packed**: added Java arguments.

1.0.0-BETA
^^^^^^^^^^

First build proven to be working and pretty nicely. Now, let's spice up it
a little with bunch of complex mods that do not really change much besides
the look of the game and add helpful utilities for SMP.

Most of these mods can and probably will be removed if test server shows bad
performance or RAM usage becomes too high. Despite it may seem it's a little
much of mods, they're mostly small additions.

:Added:
   - **DamageTilt**: ah, classic feature back from 1.2.5! When you get
     damaged, your camera tilts towards direction of the damager.
   - **Biomes O' Plenty**: adds variety of pretty biomes.
   - **Decorative Blocks**: decorative blocks.
   - **YUNG's Better Mineshafts**: amazing mineshafts in replacement to
     boring ones from vanilla.
   - **FTB GUI Library**: needed for JEI and other FTB mods.
   - **FTB Teams**: adds teams management.
   - **FTB Chunks**: allows teams to claim their chunks.
   - **Macaw's Roofs**: what beautiful house is lacking? A nice roof!
   - **Macaw's Bridges**: very cool bridges, bridges are cool.
   - **Macaw's Windows**: we love transparent glass.
   - **Macaw's Doors**: and nice doors.
   - **Macaw's Trapdoors**: in addition to other mods of this series.
   - **Just Enough Resources**: shows where to search for resources in JEI.
   - **JEI Enchantment Info**: why you need Google? Just look in the game.
   - **Mouse Tweaks**: scrolling and faster pickup, we like shortcuts.
   - **Cat Jammies**: cats actually catJAM to music disks. MUST HAVE.
   - **FastWorkbench**: workbench do be zooming. Never could've thought I
     needed that.
   - **Better Ping Display**: actually better ping display, screw you bars!
   - **RandomPatches**: bunch of random patches to fix bugs and improve order
     of things.
   - **AI Improvements**: not a big fixer, but still helps a little with
     entities performance.
:Updated:
   - **Quark** to the newest version.
:Changed:
   - **Quark**: disabled greener grass on client because it's too green.
     You can re-enable it if you want.

1.0.0-ALPHA
^^^^^^^^^^^

Initial untested build... for public testing!

:Added:
   - **Create**: duh, that's what the server is being made for!
   - **Macaw's Furniture**: pretty furniture :)
   - **SkinChanger**: as we're running in offline, there should be a way
     to set your skin.
   - **JEI**: allows viewing how to craft Create items.
   - **Quark**: bunch of small improvements to base game.
   - **Chisel & Bits**: was requested, allows building in small bits.
   - **Jade**: allows to view what block you look at.
