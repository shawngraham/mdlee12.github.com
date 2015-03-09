---
layout: default
---

<div class="row">
<div class="container">
<div class="jumbotron">
<h1>About Michael Lee</h1>
</div></div></div>
<div class="row">
<div class="container">
<div class="col-md-12">
<p class="lead">
Welcome to middlee.com, a website of data visualizations, analysis, inquiry and thoughtless musings. I'm a data scientist interested in sports, education, and psychology. My recent experience involves analyses relating to education measures (student demographics, attendance, performance) and sports research (player comparisons, arbitration information, and salary compensation). I keep this site to display my work, and I hope you find it interesting! If you do, let me know!</p></div>
<div class="container">
<div class=".col-xs-6 col-sm-6">
<img src="/images/profile.jpg" class="img-responsive" itemprop="image" />
</div>
<div class="page-header">
  <h1>Contact</h1>
</div>
<div class=".col-xs-6 .col-sm-6">
<h1><small>Email</small></h1>

	<a href="#myModal" data-toggle="modal">Send me an email!</a>
    	<div id="myModal" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
      	  <div class="modal-dialog">
       	  <div class="modal-content">
		<div class="modal-header">
		    <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
		    <h4 class="modal-title">Contact Form</h4>
		</div>
		<div class="modal-body">
			<form id="commentForm" class="form-horizontal" method="post" action="http://formspree.io/mdlee12@gmail.com">
			 <input type="hidden" name="_next" value="about" />
			 <div class="form-group">
				<label class="control-label col-md-4">Name</label>
				<div class="col-md-6">
				    <input type="text" class="form-control required" name="name">
				</div>
			    </div>
			    <div class="form-group">
				<label class="control-label col-md-4">Your Email Address</label>
				<div class="col-md-6 input-group">
				<span class="input-group-addon">@</span>
				    <input type="email" class="form-control" name="email">
				</div>
			    </div>
			    <div class="form-group">
				<label class="control-label col-md-4">Question or Comment</label>
				<div class="col-md-6">
				    <textarea rows="6" class="form-control" name="comments"></textarea>
				</div>
			    </div>
			    <div class="form-group">
				<div class="col-md-6">
				    <button type="submit"class="btn btn-custom pull-right" id="send_btn">Send</button>
				</div>
			    </div>
			</form>
	<script>
	   
	$(document).ready(function() {
 		$('#commentForm').formValidation({
			framework: 'bootstrap',
			icon: {
			    valid: 'glyphicon glyphicon-ok',
			    invalid: 'glyphicon glyphicon-remove',
			    validating: 'glyphicon glyphicon-refresh'
			},
			fields: {
			    name: {
				validators: {
				    notEmpty: {
				        message: 'Name is a required field'
				    }
				}
			    },
			    email: {
				validators: {
				    notEmpty: {
				        message: 'Email is a required field'
				    }
				}
			    },
			    comments: {
				validators: {
				    notEmpty: {
				        message: 'Comments is a required field'
				    }
				}
			    }
			}
		    });
		});
	</script>



        </div><!-- End of Modal body -->
        </div><!-- End of Modal content -->
        </div><!-- End of Modal dialog -->
    </div>




<h1><small>Github</small></h1>
<a href="https://github.com/mdlee12">Contribute to my code.</a>
<h1><small>Linkedin</small></h1>
<a href="https://www.linkedin.com/in/middlee">All professional inquiries welcomed!</a>
<h1><small>Twitter</small></h1>
<p class="text-justify">I mostly tweet about sports, data, and pop culture. Get at me!</p>
<div class="twitter-timeline" href="https://twitter.com/mlee_mke" data-widget-id="568835700255363072">Tweets by @mlee_mke
	<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
</div>
</div>
</div>
<hr></hr>

</div>
</div>