# Bootstrap

**-Layout-**  
1. 12 columns Grid System  
`col-xs-*`  
`col-sm-*`  
`col-md-*`  
`col-lg-*`  

2. class="container", class="row", class="col-md-8", class="col-md-4"  

3. mixed style in one class to suit different devices  
`<div class="col-xs-6 col-sm-8 col-md-9 col-lg-10">...</div>`  
`<div class="col-xs-6 col-sm-4 col-md-3 col-lg-2">...</div>`  

4. Content order : push / pull  
`<div class="col-md-6 col-md-push-6">Left</div>`  
`<div class="col-md-6 col-md-pull-6">Right</div>`  

5. Nesting  

6. offset  
`<div class="col-md-6 col-md-offset-4">Move 4 grid to right</div>`  

7. Display / Hide  
visible/hidden-xs/sm/md/lg;  
`<p class="visible-xs alert alert-info">Download app!</p>`  