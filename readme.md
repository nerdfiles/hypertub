#HyperTUB

##MVP

1. Symbol Tagging
   1. “Sidebar” that provides code symbol summaries based on the location  
      of the primary codeblock within the viewport of the browser.
2. Updated Organelles
   1. Identification of (a) watched symbols, (b) saved symbols that have been  
      mapped, (c) group saved symbols
3. Browser Blame
   1. If the User closes a browser tab or window, the App should ask to harvest  
      any code blocks (Page Visibility state model implies loss codeblock)
   2. Set App mode to continuously store to Dropbox on “blame” or to ask in 
      a non-blocking “sidebar”.

##Implementation

We’ll first try to implement this browser feature in Breach.cc Browser, 
which should give us a reference implementation for extrapolated use-cases 
and alternative use-cases.
