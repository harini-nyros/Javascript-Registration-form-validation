/** method for user name validations **/
var barspan=0;
var temp=9.0000;
var usrcount=0;
var pwdcount=0;
var fnamecount=0;
var lnamecount=0;
var filecount=0;
var daycount=0;
var monthcount=0;
var yearcount=0;
var hobcount=0;
var countrycount=0;
var phcount=0;
function user_validation(user) 
{
    var usrformat =/^[a-zA-Z0-9]+$/;
	if(user.value=='')
	{	
		document.getElementById('message').innerHTML="<img src='images/bullet_error.png'>Enter User name";
			user.focus();
			return false;
   


	}
   else if(user.value.match(usrformat)&&(user.value.length)>=5 && (user.value.length<=8))
    {
		
       if(usrcount<=0)	
		barspan=barspan+temp+0.0001;
		usrcount++;
        	document.getElementById('bar').style.width=barspan+'%';
        document.getElementById('message').innerHTML="";
        return true;
    }
    else {
			document.getElementById('message').innerHTML="<img src='images/bullet_error.png'>User name should be Alpha Numeric and length between 5 to 8";
			user.focus();
			return false;
   
         }


}

/** method for password validations **/   

function pwd_validation(pwd) {
    var pwdformat= /^[a-zA-Z0-9]+$/;
	if(pwd.value=='')
	{	
		
		document.getElementById('pmessage').innerHTML="<img src='images/bullet_error.png'>Enter password";
			pwd.focus();
			return false;

	}
    else  if(pwd.value.match(pwdformat)&&(pwd.value.length)>=6)
	{
       	if(pwdcount<=0)
		barspan=barspan+temp;
		pwdcount++;
        document.getElementById('bar').style.width=barspan+'%';
        document.getElementById('pmessage').innerHTML="";
        return true;
    }
    else {
			
        document.getElementById('pmessage').innerHTML="<img src='images/bullet_error.png'>password should be of 6 characters and alphanumeric";
        pwd.focus();
        return false;
    }

}
/** method for firstname validation **/
function fname_validation(fname) 
{
	if(fname.value=='')
	{	
		
		document.getElementById('fmessage').innerHTML="<img src='images/bullet_error.png'>Enter Firstname";
			fname.focus();
			return false;

	}
    else if((fname.value.length)>=2 && (fname.value.length)<=6)
    {
        	if(fnamecount<=0)
		barspan=barspan+temp;
		fnamecount++;
        document.getElementById('bar').style.width=barspan +'%';
        document.getElementById("fmessage").innerHTML="";
        return true;
    }
    else {
		
        document.getElementById('fmessage').innerHTML="<img src='images/bullet_error.png'>first name should between 2 to 6 characters";
        fname.focus();
        return false;
    }

}
/** method for lastname validation **/
function lname_validation(lname) 
{
	if(lname.value=='')
	{	
		
		document.getElementById('lmessage').innerHTML="<img src='images/bullet_error.png'>Enter Lastname";
			lname.focus();
			return false;

	}
    else if((lname.value.length)>=2 && (lname.value.length)<=15)
    {
        if(lnamecount<=0)
		barspan=barspan+temp;
		lnamecount++;
        document.getElementById('bar').style.width=barspan +'%';
        document.getElementById("lmessage").innerHTML="";
        return true;
    }
    else
    {
		
        document.getElementById('lmessage').innerHTML="<img src='images/bullet_error.png'>last name should between 2 to 15 characters";
        lname.focus();
        return false;
    }



}
/** method for picture validation **/
function filename_validation(filename) 
{
    var fileName = filename.value;
    var ext = fileName.substring(fileName.lastIndexOf('.') + 1);
	
    if(ext!= "gif" && ext!= "GIF"  && ext!= "jpg" && ext!= "JPG" && ext!= "png")
    {
        document.getElementById("imessage").innerHTML="<img src='images/bullet_error.png'>Upload Gif,jpg or png images only";
        filename.focus();
        return false;
    }
    else
    {
         if(filecount<=0)
		barspan=barspan+temp;
		filecount++;
        document.getElementById('bar').style.width=barspan+'%';
        document.getElementById("imessage").innerHTML=""
        return true;
    }

}
/** method for day validation **/
function day_validation(day)
{
    if(day.value =='selectday')
    {
        document.getElementById("dobmessage").innerHTML="<img src='images/bullet_error.png'>please select the day";
        day.focus();
        return false;
    }
    else
    {
        if(daycount<=0)
		barspan=barspan+temp;
		daycount++;
        document.getElementById('bar').style.width=barspan +'%';
        document.getElementById("dobmessage").innerHTML="";
        return true;

    }
}
/** method for month validation **/
function month_validation(month)
{
    if(month.value =='selectmonth')
    {
        document.getElementById("dobmessage").innerHTML="please select the month";
        month.focus();
        return false;
    }
    else
    {
          if(monthcount<=0)
		barspan=barspan+temp;
		monthcount++;
        document.getElementById('bar').style.width=barspan +'%';
        /** method for year validation **/
        document.getElementById("dobmessage").innerHTML="";
        return true;

    }
}
function year_validation(year)
{
    if(year.value =='selectyear')
    {
        document.getElementById("dobmessage").innerHTML="<img src='images/bullet_error.png'>please select the year";
        year.focus();
        return false;
    }
    else
    {
	 if(yearcount<=0)
		barspan=barspan+temp;
		yearcount++;
       
        document.getElementById('bar').style.width=barspan +'%';
        document.getElementById("dobmessage").innerHTML="";
        return true;

    }
}
function isOneChecked() 
{
    var chx = document.getElementsByName('hobbies');
    for (var i=0; i<chx.length; i++)
    {
        if (chx[i].checked==true)
        {
	    if(hobcount<=0)
		barspan=barspan+temp;
		hobcount++;
            document.getElementById('hobmes').innerHTML="";
            return true
        }
    }
    document.getElementById('hobmes').innerHTML="<img src='images/bullet_error.png'>Please select any one hobby";
    return false;
} 

function country_validation(country)
{
    if(country.value==null || country.value=="")
    {
        document.getElementById("countrymessage").innerHTML="please select the country";
        country.focus();
        return false;
    }
    else
    {
        if(countrycount<=0)
		barspan=barspan+temp;
		countrycount++;
        document.getElementById('bar').style.width=barspan +'%';
        document.getElementById("countrymessage").innerHTML="";
        return true;
    }

}
/** method for phonenum validation **/
function phnum_validation(phnum) 
{
    var phoneregex=/^(\+)(\d{2})(\s)(\({1})(\d{3})(\){1})(\-{1})(\d{3})(\-{1})(\d{4})$/;
    if(phnum.value.match(phoneregex))
    {
         if(phcount<=0)
		barspan=barspan+temp;
		phcount++;
        document.getElementById('bar').style.width=barspan +'%'
        document.getElementById("phmessage").innerHTML="";
        return true;
    }
    else
    {
        document.getElementById("phmessage").innerHTML="phone number format should be in +91 (990)-824-7888";
        phnum.focus();
        return false;

    }
	


}

function formValidate(myForm) 
{
    var fname=myForm.firstname;
    var lname=myForm.lastname;
    var pwd=myForm.password;
    var username=myForm.username;
    var fup=myForm.filename;
    var day=myForm.day;
    var month=myForm.month;
    var year=myForm.year;
    var chx =myForm.hobbies;
    var country=myForm.country;
    var phnum=myForm.phonenum;

	
  
    if(user_validation(username) && pwd_validation(pwd) && fname_validation(fname) && lname_validation(lname) && filename_validation(fup) && day_validation(day) && month_validation(month) && year_validation(year) && isOneChecked() && country_validation(country) && phnum_validation(phnum))
	{
		document.getElementById('alert').style.visibility="visible";
        return false;
	}
  return false;

}

