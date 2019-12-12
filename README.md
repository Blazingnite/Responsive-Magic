# Responsive-Magic
HTML Emails
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <title>A Simple Responsive HTML Email</title>
        <style type="text/css">
        body[yahoo] .class {margin: 0; padding: 0; min-width: 100%!important;}
        .content {width: 100%; max-width: 600px;}
        .header {padding: 40px 30px 20px 30px;}
        .col425 {width: 425px!important;}
        img {height: auto;}
        .subhead {font-size: 15px; color: #ffffff; font-family: sans-serif; letter-spacing: 10px;}
        .h1 {font-size: 33px; line-height: 38px; font-weight: bold;}
        .h1, .h2, .bodycopy {color: #153643; font-family: sans-serif;}
        /* A Fix for Apple Mail Lack of Max-Width Support*/
        @media only screen and (min-device-width: 601px) {
        .content {width: 600px !important;}
        .col425 {width: 425px!important;}
        .col380 {width: 380px!important;}
        }
        @media only screen and (max-width: 550px), screen and (max-device-width){
          body[yahoo] .buttonwrapper {background-color: transparent!important;}
          body[yahoo] .button a {background-color: #e05443; padding: 15px 15px 13px!important; display: block!important;}
          body[yahoo] .unsubscribe {display: block; margin-top: 20px; padding: 10px 50px; background: #2f3942; border-radius: 5px; text-decoration: none!important; font-weight: bold;}
          body[yahoo] .hide {display: none!important;}
        }

        .innerpadding {padding: 30px 30px 30px 30px;}
        .borderbottom {border-bottom: 1px solid #f2eeed;}
        .h2 {padding: 0 0 15px 0; font-size: 24px; line-height: 28px; font-weight: bold;}
        .bodycopy {font-size: 16px; line-height: 22px;}
        .button {text-align: center; font-size: 18px; font-family: sans-serif; font-weight: bold; padding: 0 30px 0 30px;}
        .button a {color: #ffffff; text-decoration: none;}
        img{height: auto;}
        .footer{padding: 20px 30px 15px 30px;}
        .footercopy{font-family: sans-serif; font-size: 14px; color: #ffffff;}
        .footercopy a {color: #ffffff; text-decoration: underline;}
        </style>
    </head>
    <body yahoo bgcolor="#ffffff">
      <!-- This part is meant to overcome the lack of Max-Width Support -->
      <!-- Mainly for Outlook and IE -->
      <!--[if (gte mso 9)|(IE)]>
<table width="600" align="center" cellpadding="0" cellspacing="0" border="0">
    <tr>
        <td>
            <![endif]-->
            <table width="100%" bgcolor="#ffffff" border="0" cellpadding="0" cellspacing="0">
              <tr>
                <td>
                  <table class="content" align="center" cellpadding="0" cellspacing="0" border="0">
                    <tr>
                      <td class="header" bgcolor="#c7d8a7">
                        <table width="70" align="left" border="0" cellpadding="0" cellspacing="0">
                          <tr>
                            <td height="70" style="padding: 0 20px 20px 0;">
                              <img src="https://i.postimg.cc/vBDfDKSb/Email-Magic-Email.png"  border="0" alt=""/>
                            </td>
                          </tr>
                        </table>

                  <!--[if mso]>
                </td><td>
                <![endif]-->
                <!--[if (gte mso 9)|(IE)]>
<table width="425" align="left" cellpadding="0" cellspacing="0" border="0">
    <tr>
        <td>
        <![endif]-->
              <table class="col425" align="left" border="0" cellpadding="0" cellspacing="0" style="width: 100%; max-width: 425px;">
                <tr>
                  <td height="70">
                    <table width="100%" border="0" cellspacing="0" cellpadding="0">
                      <tr>
                        <td class="subhead" style="padding: 0 0 0 3px;">
                          CREATING
                        </td>
                      </tr>
                      <tr>
                        <td class="h1" style="padding: 5px 0 0 0;">
                          Responsive Email Magic
                      </td>
                    </tr>
                  </table>
                </td>
              </tr>
            </table>
              <!--[if (gte mso 9)|(IE)]>
      </td>
  </tr>
</table>
<![endif]-->
</td>
</tr>
        <tr>
          <td class="innerpadding borderbottom">
            <table width="100%" border="0" cellspacing="0" cellpadding="0">
              <tr>
                <td class="h2">
                  Welcome to our responsive email!
                </td>
              </tr>
              <tr>
                <td class="bodycopy">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. In tempus adipiscing felis, sit amet blandit ipsum volutpat sed. Morbi porttitor, eget accumsan dictum, nisi libero ultricies ipsum, in posuere mauris neque at erat.
                </td>
              </tr>
            </table>
          </td>
        </tr>

        <tr>
          <td class="innerpadding borderbottom">
            <table width="115" align="left" border="0" cellspacing="0" cellpadding="0">
              <tr>
                <td height="115" style="padding: 0 20px 20px 0;">
                  <img src="https://i.postimg.cc/wvFQcTWY/News-Letter-Icon.png"  border="0" alt="Newsletter Icon"/>
                </td>
              </tr>
            </table>
            <!--[if (gte mso 9)|(IE)]>
     <table width="380" align="left" cellpadding="0" cellspacing="0" border="0">
       <tr>
         <td>
   <![endif]-->
        <table class="col380" align="left" border="0" cellspacing="0" cellpadding="0" style="width: 100%; max-width: 380px;">
          <tr>
            <td>
              <table width="100%" border="0" cellspacing="0" cellpadding="0">
                <tr>
                  <td class="bodycopy">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In tempus adipiscing felis, sit amet blandit ipsum volutpat sed. Morbi porttitor, eget accumsan dictum, nisi libero ultricies ipsum, in posuere mauris neque at erat.
                  </td>
                </tr>
                <tr>
                  <td style="padding: 20px 0 0 0;">
                    <table class="buttonwrapper" bgcolor="#e05443" border="0" cellspacing="0" cellpadding="0">
                      <tr>
                        <td class="button" height="45">
                          <a href="#">Claim Yours!</a>
                        </td>
                      </tr>
                    </table>
                  </td>
                </tr>
              </table>
            </td>
          </tr>
        </table>
        <!--[if (gte mso 9)|(IE)]>
      </td>
    </tr>
</table>
<![endif]-->
</td>
</tr>

<tr>
  <td class="innerpadding borderbottom">
    <img src="https://i.postimg.cc/0NNLQHng/image-responsive.png" width="100%" border="0" alt="" />
  </td>
</tr>
<!-- footer -->
<tr>
  <td class="footer" bgcolor="#44525f">
    <table width="100%" border="0" cellspacing="0" cellpadding="0">
      <tr>
        <td align="center" class="footercopy">
          &amp;reg; Someone, somewhere 2019<br/>
          <a href="#" class="unsubscribe"><font color="#ffffff">Unsubscribe</font></a><span class="hide"> from this newsletter instantly</span>
        </td>
      </tr>
      <tr>
        <td align="center" style="padding: 20px 0 0 0;">
          <table border="0" cellspacing="0" cellpadding="0">
            <tr>
              <td width="37" style="text-align: center; padding: 0 10px 0 10px;">
                <a href="#">
                  <img src="https://i.postimg.cc/sgsschhf/Metrize-Icons-Facebook-Responsive.png" width="37" height="37" alt="Facebook"/>
                </a>
              </td>
              <td width="37" style="text-align: center; padding: 0 10px 0 10px;">
                <a href="#">
                  <img src="https://i.postimg.cc/zB1jb8QQ/Twitter-Metrize-Icons-Responsive.png" width="37" height="37" alt="Twitter"/>
                </a>
              </td>
            </tr>
          </table>
        </td>
      </tr>
    </table>
  </td>
</tr>
</table>
        </td>
      </tr>
</table>
    </body>
</html>
