// JavaScript Document
$(document).ready(function(){
	$('.dropbtn').click(function(){
	   var drop=$(this).data("target");
	   if($(this).hasClass("btnactive"))
	   {
		   $(drop).removeClass("active");
		   $(drop).slideUp();
		   $(this).html('<i class="fa fa-plus" aria-hidden="true"></i>');
		   $(this).removeClass("btnactive");
	   }
	   else{
		  $(".btnactive").html('<i class="fa fa-plus" aria-hidden="true"></i>');
	      $(".btnactive").removeClass("btnactive");
		  $(this).html('<i class="fa fa-minus" aria-hidden="true"></i>');
	      $(this).addClass("btnactive");
		 
	      $('.active').slideUp();	
	      $(drop).addClass("active");
	      $(drop).slideDown();
	   }
	})
});