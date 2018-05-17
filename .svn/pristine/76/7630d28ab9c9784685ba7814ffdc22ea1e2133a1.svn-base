



function scrolldiv(idDiv,classAdd) {
    $(function () {
        $(window).scroll(function () {
            {
            var posDiv=($("#"+idDiv).height())+$("#"+idDiv).position().top;
            var posScreen=$(window).scrollTop()+$(window).height();
            if(posDiv<posScreen){
                $("#"+idDiv+"").addClass(classAdd+"");
                $("#"+idDiv+"").css("opacity",1);
            }
                }
        })
    })

}

scrolldiv("section4","section4e");
scrolldiv("section5","section5e")
scrolldiv("section6","section6e");
scrolldiv("section7","section7e1");
scrolldiv("parasection1","section7e2")
scrolldiv("parasection2","section7e3")
scrolldiv("parasection3","section7e4")
scrolldiv("section8","section8e");
scrolldiv("section9","section9e");


 function myFunction9() {
     var a = $(document).scrollTop();
  if (a > 1) {
         document.getElementById("myBtn").style.display ="block";
     } else {
         document.getElementById("myBtn").style.display ="none";
     }
 }

function openCloseNav()
{
    if(document.getElementById("navmenuin").style.display == "block")
	  	document.getElementById("navmenuin").style.display = "none";
	else document.getElementById("navmenuin").style.display = "block";
}

window.onscroll = function () {
    myFunction9()
};


function myFunctiondrop() {
    document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(e) {
    if (!e.target.matches('.dropbtn')) {
        var myDropdown = document.getElementById("myDropdown");
        if (myDropdown.classList.contains('show')) {
            myDropdown.classList.remove('show');
        }
    }
}
//go to top button
 $('#myBtn').click(function(){$('html, body').animate({ scrollTop: '0px' },1000);})