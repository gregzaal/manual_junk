
************
Review Notes
************


3d_interaction
==============

- Very verbose
- Will be removed and split up when restructuring happens
  

animation
=========

- Contains several empty files
- Introduction is more of a pretty index page
- Some pages have double headings (e.g. `basics/actions.rst`)
- key_frames page is a stub
- Some strange formatting in `editors/graph/editing.rst` and `editors/graph.rst` (duplication too?)
- `editors/timeline.rst` contains first-person notes, strange roman-numeral headers,
  and bad indentation (long image captions)
- Quite verbose in places
- No need to include separate pages for animating lamps, materials, cameras, etc.
  

composite_nodes
===============

- Contains some `FIXME(Template Unsupported...` because compositing nodes work the same as material nodes.
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
- Move `ruler_and_protractor.rst` to a better place
  

modeling
========

- Remove everything not related to actual modeling (e.g. objects, parenting, empties should all be moved somewhere else)
- Clean up index page (rather than linking to every page in a sub-folder, just use the ``index.rst`` in the sub-folder)
- Italic text used as mock-headings (better to use actual headings)
- Incorrect header syntax (using `*`s for subheadings)
- Contains some empty files and plenty of `TODO` comments
- Curves sections contain some old incorrect info
- Some sections (e.g. `meshes/editing/duplicating/screw.rst`) have an unnecessarily large amount of text.
- Remove info about the history of tools (we only document the current state of blender)
- Most pages need a thorough review, possibly rewriting too.
- In selection basics page, mention that selection can be changed to :kbd:`LMB` in the user preferences,
  although this manual will always refer to the default hotkeys.
- Quite a lot of duplication on selection tool descriptions.