---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.



<!DOCTYPE html><html><head><meta name="renderer" content="webkit"><meta http-equiv="X-UA-COMPATIBLE" content="IE=edge,chrome=1"/><title>南京航空航天大学主页平台管理系统 冯爱民--中文主页--首页</title><META Name="keywords" Content="机器学习，异常检测，系统能力培养冯爱民,Amy Feng" />
<META Name="description" Content="冯爱民,Feng Aimin,南京航空航天大学主页平台管理系统机器学习，异常检测，系统能力培养冯爱民,Amy Feng" />
<META Name="format-detection" Content="telephone=no" />





<meta charset="UTF-8"><link rel="stylesheet" type="text/css" href="/_ts/zwmb3/css/default.css"><link rel="stylesheet" type="text/css" href="/_ts/zwmb3/css/style.css"><script language="javascript" src="/system/resource/js/jquery/jquery-latest.min.js"></script><script src="/_ts/zwmb3/js/jquery.nicescroll.js" type="text/javascript"></script><script src="/_ts/zwmb3/js/style.js" type="text/javascript"></script><script src="/_ts/zwmb3/js/indexSlide.js"></script><!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->

<!--Announced by Visual SiteBuilder 9-->
<link rel="stylesheet" type="text/css" href="/_ts/zwmb3/_sitegray/_sitegray_d.css" />
<script language="javascript" src="/_ts/zwmb3/_sitegray/_sitegray.js"></script>
<!-- CustomerNO:77656262657232307764465550555742000200024453 -->
<link rel="stylesheet" type="text/css" href="/zwmb3/index.vsb.css" />
<script type="text/javascript" src="/system/resource/js/vsbscreen.min.js" id="_vsbscreen" ></script>
<script type="text/javascript" src="/system/resource/js/counter.js"></script>
<script type="text/javascript">_jsq_(1001,'/index.jsp',-1,1484774342)</script>
</head>
<body > <div style='width:0px;height:0px;overflow: hidden;'><img src=""  /></div>







<style type="text/css">
 body{
background-image:url(/_ts/zwmb3/images/bodyBack.png);
background-color: #ffffff;
}
</style>



<div class="headerWrap" style="    z-index: 999;    position: relative;">
<div class="header  clearfix">
<dl class="logo clearfix">
<dt>




<script> var _tsites_com_view_mode_type_=8;</script>
<a target="_blank" href="http://faculty.nuaa.edu.cn"><img  src="/_resources/group1/M00/00/28/CgDSRWNcygiAP0tsAAAd59V99Fg736.png"  /></a></dt>
<dd>教师个人主页 </dd></dl><div class="nav clearfix">
                    <ul class="nav_1" id="MenuBar1" style="visibility: hidden;">
 <li class="firstLi"><h3><a href="/fam/zh_CN/index/124461/list/index.htm">首页</a></h3>
                </li>

 <li ><h3><a href="/fam/zh_CN/zhym/124462/list/index.htm">科学研究</a></h3>
                    <div class="dropDiv">

                        <a href="/fam/zh_CN/yjgk/124463/list/index.htm">研究领域</a>
                        <a href="/fam/zh_CN/lwcg/124464/list/index.htm">论文成果</a>
                        <a href="/fam/zh_CN/zlcg/124465/list/index.htm">专利</a>
                        <a href="/fam/zh_CN/zzcg/124466/list/index.htm">著作成果</a>
                        <a href="/fam/zh_CN/kyxm/124467/list/index.htm">科研项目</a>
                    </div> 
                </li>

 <li ><h3><a href="/fam/zh_CN/zhym/124468/list/index.htm">教学研究</a></h3>
                    <div class="dropDiv">

                        <a href="/fam/zh_CN/jxzy/124469/list/index.htm">教学资源</a>
                        <a href="/fam/zh_CN/skxx/124470/list/index.htm">授课信息</a>
                        <a href="/fam/zh_CN/jxcg/124471/list/index.htm">教学成果</a>
                    </div> 
                </li>

 <li ><h3><a href="/fam/zh_CN/hjxx/124472/list/index.htm">获奖信息</a></h3>
                </li>

 <li ><h3><a href="/fam/zh_CN/zsxx/124473/list/index.htm">招生信息</a></h3>
                </li>

 <li ><h3><a href="/fam/zh_CN/xsxx/124474/list/index.htm">学生信息</a></h3>
                </li>

 <li ><h3><a href="/fam/zh_CN/img/124475/list/index.htm">我的相册</a></h3>
                </li>

</ul>

                    <ul class="nav_2"  id="cqjtdxzwmbdpqh"  style="display:none">
                        <li class="moreNav" >
                            <h3><a href="#">更多</a></h3>
                            <ul class="moreNavUl" id="MenuBar2" >
                        
                            </ul>
                        </li>
                    </ul>
                </div>

    
<script type="text/javascript">
jQuery(document).ready(function(){
    var cqjtdxzwmbdpqh = jQuery("#cqjtdxzwmbdpqh").width()
    if(cqjtdxzwmbdpqh<=0)
    {
        cqjtdxzwmbdpqh = 100;
    }
    var totalwidth =jQuery("#cqjtdxzwmbdh").width()-jQuery("#cqjtdxzwmbdpqh").width()-jQuery(".dropMenulage").width()-100;

    var allliwidth = 0;
    var othernavary = new Array();
    var MenuBar2 = jQuery("#MenuBar2")[0];
    var MenuBar1 = jQuery("#MenuBar1");
    var navliobjlist =  jQuery("#MenuBar1 > li");
    
    for(var i=0;i<navliobjlist.length;i++)
    {
        var liobj = navliobjlist.get(i);
        if(liobj)
        {
            var jliobj = jQuery(liobj);
            var liwidth = jliobj.width();
            allliwidth=allliwidth+liwidth+20;
            if(allliwidth>=totalwidth)
            {
                var templiobj = jliobj;      
                othernavary.push(templiobj);
                MenuBar1[0].removeChild(jliobj[0]);
            }
        }
    }
//能够显示全部的导航
    if(allliwidth<totalwidth)
    {
        jQuery(".dropMenu.dropMenumore").css("display","none");
    }else
    {
    var newinput = "";
    var MenuBar2obj = jQuery("#MenuBar2");
    for(var i=0;i<othernavary.length;i++)
    {
        var tempotherli = jQuery(othernavary[i]);          
        var fdiv = jQuery("<div class='item'><h3></h3></div>").append( tempotherli.find(" h3 a"));
        var sdiv = tempotherli.find("div.dropdown");
        var iobj = sdiv.find("i");
        if(iobj)
        {
             iobj.remove();           
        }
        sdiv = sdiv.addClass("dropdown2")    
        if(sdiv)
        {
            fdiv.append(sdiv);
        }
        MenuBar2obj.append(fdiv);        
    }}
    jQuery("#MenuBar1").css("visibility","visible");
});
</script> 


<div class="headerRight">
<ul>
<script language="javascript" src="/system/resource/tsites/tsitesclick.js"></script>
<script> var _tsites_com_view_mode_type_=8;</script>


		<li class="login"><a href="javascript:void(0);" title="手机版" onclick="_vsb_multiscreen.setDevice('mobile')">手机版</a></li>






    <li class="EN"><a href="http://faculty.nuaa.edu.cn/fam/en/index.htm">En</a></li>
</ul>



<script language="javascript" src="/system/resource/tsites/com/search/tsitesearch.js"></script><script language="javascript" src="/system/resource/js/base64.js"></script><div class="search">
                <form action="/fam/zh_CN/search/124461/search/result.htm" method="post" id="searchform58244" style="display:inline" onsubmit="return (new TsiteSearch()).checkSearch('searchform58244','keyWord_temp');">
 <input type="hidden" name="tsites_search_content" id="tsites_search_content" value='' /><input type="hidden" name="_tsites_search_current_language_" id="_tsites_search_current_language_" value='zh_CN' /><script>var current_language = "zh_CN";</script>                        
<input type="text"  name="keyWord_temp" id="keyWord_temp" value="" class="srhtxt" />
                        <input type="button" value="" class="srhbtn" onclick="submitvalue()"/>
                    </form> 
                    </div>

<script>
function submitvalue()
{

	var values = $('#keyWord_temp').val();
	if(values.length>0)
	{
			$('#searchform58244').submit();
	}
	

}




</script>



</div></div></div>
<div class="mainWrap">
<div class="mainInfomation clearfix">
<div class="photoWrap">
<div class="photoInfo">
<div class="photo">

<div class="img"><span><img id="u_u7_4861pic" /></span></div><script language="javascript" src="/system/resource/tsites/imagescale.js"></script>
<script type="text/javascript"> 
 var u_u7_pic = new ImageScale("u_u7_",120,180,true,true);u_u7_pic.addimg("/_resources/group1/M00/00/15/CgDSRWNb55aAbtN0AAFi4y7U_vM098.png","","冯爱民","4861");
</script>
</div>
<div class="backPhoto"></div></div><div class="like" id="_parise_imgobj_u8"><span id="_parise_obj_u8"></span></div><script language="javascript" src="/system/resource/tsites/TsitesPraiseUtil.js"></script>
<script> var _TsitesPraiseUtil_u8= new TsitesPraiseUtil();_TsitesPraiseUtil_u8.setParam({'nodeid':'_parise_obj_u8','iscanclickidobj':'iscanclick_parise_obj_u8','pdtype':'0','imageid':'_parise_imgobj_u8','apptype':'index','basenum':'0','uid':'4861','homepageid':9279,'limttype':'specilpage','limithour':24,'contentid':0});</script>
</div>
<div class="info clearfix">









<div><i class="before"></i>个人信息<i class="after"></i></div><img src="/_ts/zwmb3/images/info.png"> <span>冯爱民</span><script> var _tsites_com_view_mode_type_=8;</script>
<script language="javascript" src="/system/resource/tsites/tsitesencrypt.js"></script></div>
<div class="infoCont">








 <div>
                 <span> <b>招生学科专业：</b><br>
             计算机科学与技术 -- 【招收硕士研究生】 -- 计算机科学与技术学院<br/>软件工程 -- 【招收硕士研究生】 -- 计算机科学与技术学院<br/>电子信息 -- 【招收硕士研究生】 -- 计算机科学与技术学院<br/></span>
 <span>性别：女<br/>
         <span>联系方式：amfeng@nuaa.edu.cn</span> 
        
            
             <span>学位：工学博士学位</span> 
    
            
             
        
           
</div><script> var _tsites_com_view_mode_type_=8;</script>

<div class="more moreInfo"><a href="javascript:;">MORE +</a></div></div></div>
<div class="personInfoWrap">
<div class="personalInfo"><img src="/_ts/zwmb3/images/profile.png"> 
<div class="bgCont">









      <div class="tit">
                            <h3>
                                <span>个人信息</span>
                                <em>Personal information</em>
                            </h3>
                        </div>
                        <div class="contMain">
                            <div class="cont otherInfo">
 <span>

     &nbsp;硕士生导师
</span>
         
          
            <span>学历：南京航空航天大学</span>
            <span>毕业院校：南京航空航天大学</span>
      
        
            
            <span>所在单位：计算机科学与技术学院/人工智能学院/软件学院</span>


        <!--学术荣誉-->


            
            
            


<!--所属院系-->



        <span>办公地点：南航将军路校区计算机学院210室</span>
     
        <span>电子邮箱：<span _tsites_encrypt_field="_tsites_encrypt_field" id="_tsites_encryp_tsteacher_tsemail" style="display:none;">c5dc4d8ac630d68c680efa96ed3ef940404d70ba5ce61cfb10540d578cc6f40c044454ec770a58c41ebf474a11af5801c57bcbbd9b4bc0f5f881689fe2c2fd736cfbfe4787f906a10088f66c97cb332a7cd61ccc386902e732dcdd1affa0d97935f1b9fc56060ee42416e6bf2d3ec5782cf08c5ee9aad6cf1d92ac3f53e8dc3b</span></span>    
<script> var _tsites_com_view_mode_type_=8;</script>





</div></div>
</div></div></div>
<div class="carouselWrap">
<div id="top">
<div class="small">
<ul>













<li class="on"><a href="javascript:;">个人简介</a></li><li class=""><a href="javascript:;">教育经历</a></li><li ><a href="javascript:;">其他联系方式</a></li>	<li class=""><a href="javascript:;">工作经历</a></li>
<li class=""><a href="javascript:;">社会兼职</a></li>


 <li class=""><a href="javascript:;">研究方向</a></li><li class=""><a href="javascript:;">团队成员</a></li>
<script type="text/javascript"> 
 var u_u21_pic = new ImageScale("u_u21_",130,155,true,true);
</script>
</ul></div>


<!-- 下面这个div是二维码容器,ID不能变-->
<div id="outputu22" class="erCode"></div>
<!-- 下面是生成二维码调用的JS，不要动-->

<script src="/system/resource/qrcode/js/jquery.qrcode.js"></script>
<script src="/system/resource/qrcode/js/qrcode.js"></script>
<script>
var codeInfo = "" ==""? window.location.href:"";
jQuery(function(){
    jQuery('#outputu22').qrcode({
        text:codeInfo,
        render: !!document.createElement('canvas').getContext?"canvas":"table",//设置渲染方式  
        width: 100,     //设置宽度  
        height: 100,     //设置高度  
        correctLevel: 2,//纠错等级  
        background: "#ffffff",//背景颜色  
        foreground: "#000000",//前景颜色  
        logo:""//图像logo
    });
})
</script></div>
<div id="box">
<div id="list">
<ul><!--其他信息-->

<li class="li4 hove"><img src="/_ts/zwmb3/images/jioyu.png"> 
<div class="bgCont">













<div class="tit">
                                        <h3>
                                            <span>个人简介</span>
                                            <em>Personal profile</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="cont profile">
<p style="word-break: break-word;word-wrap: break-word;    text-indent: 2em;">
<p style="margin-top:5px;margin-right:0;margin-bottom:5px;margin-left:0;text-indent:0;text-align:left"><span style="font-family:新宋体;color:rgb(0,0,0);letter-spacing:0;font-weight:normal;font-style:normal;font-size:20px"><span style="font-family:新宋体">冯爱民</span> <span style="font-family:新宋体">南京航空航天大学副教授</span>/硕导，工学博士，主要研究方向为机器学习与模式识别、体系结构等，先后发表学术论文20余篇；热心教学，近年来围绕着教指委所倡导的系统能力培养开展了一系列教学改革，并因此获得</span><span style="font-family:新宋体;color:rgb(0,0,0);letter-spacing:0;font-weight:normal;font-style:normal;font-size:18px">2014年度获华为奖教金</span><span style="font-family:新宋体;color:rgb(0,0,0);letter-spacing:0;font-weight:normal;font-style:normal;font-size:20px"><span style="font-family:新宋体">；</span>2015/2016/2018年度学院”人才培养贡献奖”；2017</span><span style="font-family:新宋体;color:rgb(0,0,0);letter-spacing:0;font-weight:normal;font-style:normal;font-size:18px"><span style="font-family:新宋体">第一届</span>/2018第二届/2019第三届全国大学生系统能力培养大赛优秀教师；2017工信部南航“计算机系统能力培养课程”研究型教学团队核心人员；2017年度江苏省教学成果二等奖“计算机软硬件协同贯穿式人才培养的创新与实践（排名三）；2018年度南航教学创新奖获奖教师。</span><span style="font-family:新宋体;color:rgb(0,0,0);letter-spacing:0;font-weight:normal;font-style:normal;font-size:18px"><span style="font-family:新宋体">作为南航系统能力培养教学的主要负责人，接待多所兄弟院校，积极推广系统能力从理论到实践方面的经验，目前担任</span>“</span><span style="font-family:宋体;font-size:19px"><span style="font-family:宋体">工信部</span></span><span style="font-family:宋体;font-size:19px"><span style="font-family:宋体">新工科联盟系统能力推进工委会</span></span><span style="font-family:宋体;font-size:19px">”</span><span style="font-family:宋体;font-size:19px"><span style="font-family:宋体">高校</span></span><span style="font-family:宋体;font-size:19px"><span style="font-family:宋体">秘书。</span></span></p>
<p><br></p>
</p>
</div>
</div>
</div><!--教育经历--></li>
<li class="li2"><img src="/_ts/zwmb3/images/gongzuo.png"> 
<div class="bgCont"><div class="tit">
                                        <h3>
                                            <span>教育经历</span>
                                            <em>Education experience</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="cont experienceCont">
<dl>
	<dt><a style="font-size: 18px;color: #fff;"></a>2003.5&nbsp;--&nbsp;2011.6</dt>
	 <dd>  南京航空航天大学&nbsp;>&nbsp;计算机应用技术  &nbsp;>&nbsp;工学博士学位&nbsp;>&nbsp;博士研究生毕业 </dd>   
	                         
<dl>
	<dt><a style="font-size: 18px;color: #fff;"></a>1997.9&nbsp;--&nbsp;2000.4</dt>
	 <dd>  东南大学&nbsp;>&nbsp;机械设计及理论  &nbsp;>&nbsp;工学硕士学位&nbsp;>&nbsp;硕士研究生毕业 </dd>   
	                         
<dl>
	<dt><a style="font-size: 18px;color: #fff;"></a>1989.9&nbsp;--&nbsp;1993.7</dt>
	 <dd>  焦作矿业学院&nbsp;>&nbsp;机械制造  &nbsp;>&nbsp;工学学士学位&nbsp;>&nbsp;大学本科毕业 </dd>   
	                         
<dl>
	<dt><a style="font-size: 18px;color: #fff;"></a>1986.5&nbsp;--&nbsp;1989.7</dt>
	 <dd>  焦作第一高级中学  &nbsp;>&nbsp;无学位&nbsp;>&nbsp;普通高中毕业 </dd>   
	                         
</dl>
</div>
</div>






</div><!--工作经历--></li>
<li class="li1"><img src="/_ts/zwmb3/images/profile.png"> 
<div class="bgCont"><div class="tit">
                                        <h3>
                                            <span>其他联系方式</span>
                                            <em>Other Contact information</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="cont otherInfo">
<span>暂无内容</span>
</div>
</div>
</div><!--个人简介--></li>
<li class="li3"><img src="/_ts/zwmb3/images/shehui.png"> 
<div class="bgCont"><div class="tit">
                                        <h3>
                                            <span>工作经历</span>
                                            <em>Work experience</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="cont experienceCont">
<dl>
         <dt><a style="font-size: 18px;color: #fff;"></a>2009.5&nbsp;--&nbsp;至今</dt>
<dd> 南京航空航天大学 &nbsp;>&nbsp;计算机科学与技术学院&nbsp;>&nbsp;副教授  
				</dd>
	
</dl>
<dl>
         <dt><a style="font-size: 18px;color: #fff;"></a>2001.6&nbsp;--&nbsp;2009.5</dt>
<dd> 南京航空航天大学 &nbsp;>&nbsp;讲师  
				</dd>
	
</dl>
<dl>
         <dt><a style="font-size: 18px;color: #fff;"></a>2000.8&nbsp;--&nbsp;2001.5</dt>
<dd> 南京航空航天大学 &nbsp;>&nbsp;助教  
				</dd>
	
</dl>
<dl>
         <dt><a style="font-size: 18px;color: #fff;"></a>1993.7&nbsp;--&nbsp;1997.8</dt>
<dd> 焦作总工会职业中专   
				</dd>
	
</dl>

</div>
</div>

</div><!--社会兼职--></li>
<li class="li5"><img src="/_ts/zwmb3/images/yanjiu.png"> 
<div class="bgCont"><div class="tit">
                                        <h3>
                                            <span>社会兼职</span>
                                            <em>Professional affiliations</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="cont experienceCont">
<dl>
              <dt><a style="font-size: 18px;color: #fff;"></a>2018.5&nbsp;--&nbsp;2021.5</dt>
             <dd>  “工信部新工科联盟系统能力推进工委会”高校秘书</dd>
</dl>
</div>
</div>
</div><!--研究方向--></li>
<li class="li6"><img src="/_ts/zwmb3/images/tuandui.png"> 
<div class="bgCont">


<div class="tit">
                                        <h3>
                                            <span>研究方向</span>
                                            <em>Research direction</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="contMain">
                                        
暂无内容
</div>
</div></div><!--团队成员--></li>
<li class="li7"><img src="/_ts/zwmb3/images/geren.png"> 
<div class="bgCont"><div class="tit">
                                        <h3>
                                            <span>团队成员</span>
                                            <em>Team members</em>
                                        </h3>
                                    </div>
                                    <div class="contMain">
                                        <div class="cont">
暂无内容
</div>
</div>


<script type="text/javascript"> 
 var u_u29_pic = new ImageScale("u_u29_",130,150,true,true);
</script>
</div></li></ul><a id="prevLi" href="javascript:;"></a><a id="nextLi" href="javascript:;"></a></div></div></div></div>
<div class="footerWrap">
<div class="footer">
<p><script language="javascript" src="/system/resource/tsites/latestupdatetime.js"></script>
 最后更新时间：<i id="u30_latestupdatetime_year"></i>-<i id="u30_latestupdatetime_month"></i>-<i id="u30_latestupdatetime_day"></i><script>(new TsitesLatestUpdate()).getTeacherHomepageLatestUpdateTime(document.getElementById('u30_latestupdatetime_year'),document.getElementById('u30_latestupdatetime_month'),document.getElementById('u30_latestupdatetime_day'),'58119','4861','DDF63F99607742C6AD219B271B68B2B7',0,false,1484774342);</script>
<script>(new TsitesLatestUpdate()).getTeacherHomepageOpenTime(document.getElementById('u30_opentime_year'),document.getElementById('u30_opentime_month'),document.getElementById('u30_opentime_day'),'58119','4861','DDF63F99607742C6AD219B271B68B2B7',0,false,1484774342);</script>
&nbsp;&nbsp;&nbsp;
访问量：<em id="u31_click"></em><script  type='text/javascript'>jQuery(document).ready(function(){(new TsitesClickUtil()).getHomepageClickByType(document.getElementById('u31_click'),0,8,'teacher','4861','DDF63F99607742C6AD219B271B68B2B7');})</script>
</p>


 <p>版权所有©2018- 南京航空航天大学·信息化处（信息化技术中心）</p></div></div>

</body></html>

