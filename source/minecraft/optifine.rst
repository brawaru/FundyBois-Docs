Installing OptiFine to Minecraft
================================

OptiFine is well-known optimisation and customisation mod for Minecraft that
adds bunch of good features that improve look and feel, as well as optimises
game rendering engine to provide more plausible FPS.

Features of OptiFine
~~~~~~~~~~~~~~~~~~~~

Just a list of some features that OptiFine provides:

* Shaders. If you have powerful enough computer, adds fantastic shadows and
  lighting, which improves game atmosphere a ton.

* Dynamic lights. Hold torch or other emitting item in the dark to light up
  the area around you.

* Connected textures. Makes it so glass and some other blocks have a continuous
  textures instead of be displayed as separate blocks.

* Better grass, snow and water. Connects grass and snowy blocks, as well as
  improves transparency and visibility underwater.

* Disable certain details or animations. Turn off the fog for better
  visibility, disable rain obstructive rain particles or water flow animation.

You can see more complete list of features on `OptiFine site
<https://optifine.net/>`_.


Installing
~~~~~~~~~~

Via installer
^^^^^^^^^^^^^

.. admonition:: Java required to proceed
   :class: warning

   OptiFine Installer requires Java to run. You can install Java manually
   or use :doc:`Java provided by Minecraft <provided_java>` alternatively.

1. Download required version of Minecraft you install OptiFine for.

2. Download corresponding OptiFine version from `official site
   <https://optifine.net/downloads>`_.

3. Open downloaded JAR file with Java.

4. Make sure that installation directory is correct if you changed it.

5. Click ‘Install’ and wait until ‘successfully installed’ message pops up.
   This might take a while.

As a mod
^^^^^^^^

This is an alternative variant for people who wish to use other client side
mods or have failed to install OptiFine using its installer.

.. tabs::

   .. tab:: Fabric

      .. warning::
         Fabric mod loader is not officially supported by OptiFine. The
         approach described below uses a separate mod to make OptiFine
         work with Fabric.

         Expect incompatibilities with other mods, and possible crashes,
         although none were found throughout our testing.

      For instruction on how to install Fabric mods, head to
      :ref:`Fabric page <fabric_install-mods>`.

      1. Download OptiFine for your game version.

      2. Install `OptiFabric mod
         <https://www.curseforge.com/minecraft/mc-mods/optifabric>`_.

      3. Install OptiFine as a regular mod instead of opening it.

   .. tab:: Forge

      .. warning::
         Do not use Forge to install OptiFine alone. Forge is a complex mod
         loader that patches a lot of game code. You'll neglect any
         performance benefits OptiFine gives by doing so.

         Only do this if you want to install other Forge mods.

      1. Download OptiFine for your game version.

      2. Instead of opening it, :ref:`install it as a regular Forge mod
         <forge_install-mods>`.
