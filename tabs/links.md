---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Material de apoyo"
    info: "Los siguientes enlaces te llevan a contenido especifico del tema."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Hacking"
      type: id_hacking
      color: "#0096FF"
    - title: "Programación"
      type: id_programacion
      color: "#39AEA9"
    - title: "Otros"
      type: id_otros
      color: "#5534A5"

  list:
    -
   

    # hacking
    - type: id_hacking
      title: "Mis notas de hacking"
      url: "https://xord01.gitbook.io/uno-zero/about-us/whoami"
      info: "Contiene mis notas importantes sobre hacking."
  
 
  
  # Programacion
    - type: id_programacion
      title: "Stack OverFlow"
      url: "https://stackoverflow.com/"
      info: "Stack Overflow responde a preguntas de programación."
    - type: id_programacion
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools contiene material para aprender lenguajes como HTML, CSS, JavaScript, Python, SQL y mucho Java."
  
  # otros
    - type: id_otros
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools offers free online tutorials, references and exercises in all the major languages of the web. Covering popular subjects like HTML, CSS, JavaScript, Python, SQL, Java, and many more."
---
