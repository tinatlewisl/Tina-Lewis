---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: 'github.tinatlewisl.pub' 

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 140

title: Hello  
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Head Teaching Assistant
    company: Purdue Data Mine 
    company_url: 'https://datamine.purdue.edu/'
    location: West Lafayette, IN
    date_start: '2019-08-15'
    date_end: ''  
    description: |2-  
        Purdue Data Mine is the first large-scale living learning community for undergraduates from all majors, focused on Data Science for All.  
        
        Responsibilities include:  
        
        * Supervised a group of 12 TAs, organized and ran TA training meetings  
        * Contributed to writing, reviewing all R, python and SQL course projects    
        * Contributor and editor of the [DataMine example book](https://thedatamine.github.io/the-examples-book/index.html)    
---
<!DOCTYPE html>
<html lang="en">
<body>
<div id="modal" class="modal fade" role="dialog">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">{{ i18n "btn_cite" }}</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <pre><code class="tex hljs"></code></pre>
      </div>
      <div class="modal-footer">
        <a class="btn btn-outline-primary my-1 js-copy-cite" href="#" target="_blank">
          <i class="fas fa-copy"></i> {{ i18n "btn_copy" }}
        </a>
        <a class="btn btn-outline-primary my-1 js-download-cite" href="#" target="_blank">
          <i class="fas fa-download"></i> {{ i18n "btn_download" }}
        </a>
        <div id="modal-error"></div>
      </div>
    </div>
  </div>
</div>
</body>
</html>  
