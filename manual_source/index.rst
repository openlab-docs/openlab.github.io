.. Top-Level documentation file is used to start the toctree; 
   however, this file is overriden in the rendering process
   by an alternative index.html that provides a visually-pleasing 
   landing page.  Updates to this top-level item must also
   be transposed in the 'templates/index.html' file.

IRIS Documentation 
------------------------

.. toctree::
   :maxdepth: 1
   :glob:

   Overview <man-overview/index>
   Analyzer <man-analyzer/index>
   DB UI    <man-db-ui/index>
   User's Guide <guides/user>
   Administrator's Guide <guides/administrator>
   Integration Guide <guides/integration>
   Developer's Guide <guides/developer>
