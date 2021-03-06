
************
Review Notes
************

Below are some notes I made while roughly going through each chapter of the manual.
It is by no means a thorough review, there are undoubtedly other issues in each chapter that I missed.

I would highly recommend starting most chapters (almost) from scratch,
using the old version only as a reference for what might need to be included in the chapter.
This will ensure that we have correct and up-to-date info, only include info related to that chapter
(some chapters go waaay off topic) and avoid duplicate content which is hard to maintain.

The structure inside some chapters is also pretty confusing,
so starting from scratch will allow us to structure things more logically.


3d_interaction
==============

- Very verbose
- Will be removed and split up when restructuring happens
  

animation
=========

- Contains several empty files
- Introduction is more of a pretty index page
- Some pages have double headings (e.g. ``basics/actions.rst``)
- key_frames page is a stub
- Some strange formatting in ``editors/graph/editing.rst`` and ``editors/graph.rst`` (duplication too?)
- ``editors/timeline.rst`` contains first-person notes, strange roman-numeral headers,
  and bad indentation (long image captions)
- Quite verbose in places
- No need to include separate pages for animating lamps, materials, cameras, etc.
  

composite_nodes
===============

- Contains some ``FIXME(Template Unsupported...`` because compositing nodes work the same as material nodes.
- Missing many new nodes, especially (but not only) related to motion tracking
- Very verbose in places
  

data_system
===========

- Contains very old info (e.g. OOPS schemetic, data select browser)
- Some bad formatting (indentation) in linked_libraries.rst
- Outliner page uses **bold** text as mock-headings (rather use actual headings)
- Move *outliner* page to *Editors* chapter
- Remove any details about import/export formats
  (this should be documented `outside the manual <http://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts>`__)


editors
=======

This whole section needs doing :)


extensions
==========

- Weasel words ("Unlike many programs...") in introduction
- python.rst: Title and "Welcome to the Blender 2.6 Python Manual." - remove version
- Use more ``literals`` when giving code examples
- Explicitly choose python as language in code blocks.
- Some empty headings in ``python/faq.rst``
- In ``python/references.rst`` links to  specific versions are old - needs better solution?
  

getting_started
===============

- Needs ``introduction.rst``
- ``introduction`` should be renamed to avoid confusion with ``introduction.rst``
- ``installing_blender/index.rst`` doesn't link to all the pages in that section
- Some content can be moved to the main ``Editors`` chapter.
  

grease_pencil
=============

- Needs updating with all the cool new toys from gooseberry project
- Move ``ruler_and_protractor.rst`` to a better place
  

modeling
========

- Remove everything not related to actual modeling (e.g. objects, parenting, empties should all be moved somewhere else)
- Clean up index page (rather than linking to every page in a sub-folder, just use the ``index.rst`` in the sub-folder)
- Italic text used as mock-headings (better to use actual headings)
- Incorrect header syntax (using ``*``s for subheadings)
- Contains some empty files and plenty of ``TODO`` comments
- Curves sections contain some old incorrect info
- Some sections (e.g. ``meshes/editing/duplicating/screw.rst``) have an unnecessarily large amount of text.
- Remove info about the history of tools (we only document the current state of blender)
- Most pages need a thorough review, possibly rewriting too.
- In selection basics page, mention that selection can be changed to ``LMB`` in the user preferences,
  although this manual will always refer to the default hotkeys.
- Quite a lot of duplication on selection tool descriptions.
  

modifiers
=========

- Is mostly fine (had a pretty thorough review recently),
  though it could use some more stack-order examples in ``the_stack.rst``
- The Warp Modifier needs a "Usage" section to explain how it can be used and what it is typically used for
  (it's fairly strange and unintuitive)
  

motion_tracking
===============

Currently there is a single index page under /motion_tracking,
this should be split up into a logical file structure and updated with all the new features.

At the moment, the best documentation for the motion tracker can only be found in the long history of release notes:

.. list-table::

   * - `2.62 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.62/Motion_Tracker>`__
     - `2.63 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.63/Motion_Tracker>`__
     - `2.64 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.64/Motion_Tracker>`__
     - `2.65 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.65/More_Features>`__
     - `2.67 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.67/Motion_Tracker>`__
     - `2.68 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.68/Motion_Tracker>`__
     - `2.69 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.69/Motion_Tracker>`__
     - `2.70 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.70/Motion_Tracker>`__
     - `2.71 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.71/More_Features>`__
     - `2.72 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.72/More_Features>`__
     - `2.73 <http://wiki.blender.org/index.php/Dev:Ref/Release_Notes/2.73/More_Features>`__

  
physics
=======

- Needs updating:
   - Doesn't contain anything about the rigid body system
   - Doesn't contain anything about fire simulation
   - Fluid docs are very old
- Remove info about game-engine physics.
- ``soft_body/simple_examples.rst`` has terrible english and grammar.
- Some empty pages
- Move info about smoke/fire materials to the Render chapter (and add info for cycles)
- Move appendices to troubleshooting chapter, or include info in main docs.
  

preferences
===========

Seems mostly fine, except:

- ``file.rst`` seems outdated
- *Screencast* section in ``system.rst`` is TODO
  

render
======

- Cycles section needs lots of reorganizing and updating with new features.
- Blender Render section was thrown together quickly, needs an introduction,
  and is quite fragmented (contains lots of sub-folders and files).
- Lighting section shouldn't contain any whole pages of World-related stuff (e.g. AO),
  though it can be mentioned in the introduction.
- Some things relating to only Blender Render are in the root
  

rigging
=======

- Much of the armature-related stuff is very verbose and like a tutorial
- Some empty pages
- Constraints pages have inconsistent formatting and several TODO notes.
- Remove constraints not available in current blender version.
- 'Posing' section doesn't need to mention constraints, that should be covered in the constrains section.
