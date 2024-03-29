=============================
tinymce_ResponsiveFilemanager
=============================
Developed by https://github.com/trippo/ResponsiveFilemanager/ edit by DXGCMS for Content Management Systems, easy to install and mess with.
This is not Developed by DXGCMS just edited for easy installs.
=============================
To Use with TINYMCE 4.1.x
=============================
Add  responsivefilemanager to the tinymce plugin list,
Add in a setting call image_folder to set the image folder from the root of the site as in if your folder is /media/img/ just add that into the setting so it looks like
image_folder: "media/img/" this is a tinymce setting so it should all look like,

tinymce.init({
	selector: "textarea.tinymce",theme: "modern",
	plugins: [
		 "advlist autolink link image lists charmap print preview hr anchor pagebreak",
		 "searchreplace wordcount visualblocks visualchars insertdatetime media nonbreaking",
		 "table contextmenu directionality emoticons paste textcolor responsivefilemanager"
   ],
   toolbar1: "undo redo | bold italic underline | alignleft aligncenter alignright alignjustify | bullist numlist outdent indent | styleselect",
   toolbar2: "| link unlink anchor | image media | forecolor backcolor  | print preview code ",
   image_advtab: true,
	image_folder: "/media/img/"
 });
 
that's all you have to do how easy was that :)

*********************************************************
! Responsive FileManager for TinyMCE
*********************************************************

Responsive FileManager is a free open-source file manager made with the jQuery library, CSS3, PHP and HTML5 that offers a nice and elegant way to upload and insert files, images and videos. You can use it as external plugin for TinyMCE version 4.x. and you can also use it as a stand-alone file manager to manage and select files. The script automatically creates thumbnails of images for the preview list and can create also external thumbnails to use in your cms or site. It can be configured for automatic resizing of uploaded images or to automatically limit the size. You can personalize the configuration for each folder. You can set a subfolder as the root and change the configuration for each user, page or FileManager call. Is compatible with multi-user mode and you can edit images with aviary editor, sorting files.

DEMO AND DOCUMENTATION: http://www.responsivefilemanager.com/

Released under Creative Commons Attribution-NonCommercial 3.0 Unported License.

Creator : info@albertoperipolli.com - tr1pp0

*********************************************************
! Localization
*********************************************************
- AZE [Elshad Agayev]
- BGR [Stanislav Panev]
- BRA [paulomanrique]
- CZE [jlusticky]
- CHI [Richard Yang]
- ENG
- ESP [Roberto Santamaria] 
- FRA [Mathieu Ducharme]
- GER [Oliver Beta]
- HUN [Novak Szabolcs]
- IND [urayogi]
- ITA
- MON [Tumenzul Batjargal]
- NLD [Martijn van der Made]
- NOR [Pål Schroeder]
- Persian [web2web esf ir]
- POL [Michell Hoduń]
- POR [Sérgio Lima]
- RUS [vasromand] 
- SLO [Roman Šovčík]
- SWE [Jon Sten]
- TUR [Ahmed Faruk Bora]
- UKR [Sergey]


*********************************************************
! Credits
*********************************************************
Bootstrap => http://twitter.github.io/bootstrap/
Bootstrap Lightbox => http://jbutz.github.io/bootstrap-lightbox/
Dropzonejs => http://www.dropzonejs.com/
Fancybox => http://fancybox.net/
TouchSwipe => http://labs.rampinteractive.co.uk/touchSwipe/demos/
PHP Image Magician => http://phpimagemagician.jarrodoberto.com/
Mini icons => http://www.fatcow.com/free-icons‎
Jupload => http://jupload.sourceforge.net/
Bootbox => http://bootboxjs.com/
jQuery contextMenu => http://medialize.github.io/jQuery-contextMenu/
Bootstrap-modal => https://github.com/jschr/bootstrap-modal
jPlayer => http://jplayer.org/
QueryLoader2 => http://www.gayadesign.com/diy/queryloader2-preload-your-images-with-ease/
*********************************************************
