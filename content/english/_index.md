---
###################### hero slider ###########################
slider:
  enable : true
  slider_item:
  # slider item loop
  - bg_image : images/banner/banner-1.jpg
    animation_from : left
    #subtitle : We are here for your
    title : Education
    content : Thinking today about your own finances, education, self-improvement, <br> and investing so that money works for you will ensure that.
    pagination_icon : ti-comments # themify icon pack : https://themify.me/themify-icons
    pagination_name : Education
    button:
      enable : true
      label: More details
      link : "about/"
      
  # slider item loop
  - bg_image : images/banner/banner-2.jpg
    animation_from : up
    #subtitle : Get your
    title : Investing
    content : Everything is business, and that's how it should be viewed. Invest in stocks, in real estate, put money into gold, into cryptocurrencies. <br> All investments can be made daily, weekly, monthly, quarterly, or annually, whichever suits you.
    pagination_icon : ti-bar-chart # themify icon pack : https://themify.me/themify-icons
    pagination_name : Investing
    button:
      enable : true
      label: More details
      link : "about/"
      
  # slider item loop
  - bg_image : images/banner/banner-3.jpg
    animation_from : down
    #subtitle : Start your
    title : Trading
    content : We all invest our time, knowledge, money. What makes the difference is how much time we invest, how much we invest in our knowledge, <br> how much money we have at our disposal, and then what to invest in and how much?
    pagination_icon : ti-money # themify icon pack : https://themify.me/themify-icons
    pagination_name : Trading
    button:
      enable : true
      label: More details
      link : "about/"
      
  # slider item loop
#  - bg_image : images/banner/banner-4.jpg
#    animation_from : right
#    subtitle : We are always
#    title : Be Inspired By Best
#    content : Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor <br> incididunt ut labore et dolore magna aliqua.
#    pagination_icon : ti-package # themify icon pack : https://themify.me/themify-icons
#    pagination_name : Human Resources
#    button:
#      enable : true
#      label: More details
#      link : "about/"

########################################## Service ####################################
service:
  enable : true
  title: "Service We Provide"
  subtitle: "Best Service"
  section: "service" # showing items from usluge section
  # usluge item comes from "content/usluge" folder

######################################## About #########################################
about:
  enable : false
  bg_image : "images/background/about-bg.jpg"
  title : "Who We Are?"
  content : "Excepteur sint occaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum."
  # bullet point
  bullet_point:
  - "Business Services"
  - "Audit & Assurance"
  - "IT Control Solutions"
  - "Business Services"
  - "Audit & Assurance"
  - "IT Control Solutions"
  button:
    enable : true
    label : "Explore More"
    link : "about/"

##################################### Skill ##############################################
skill:
  enable : false
  subtitle : Our Skills
  title : Why Choose Us
  content: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusmod tempor incididunt laboris nisi ut aliquip ex ea commodo consequat. <br><br> Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur. Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum. sed perspiciatis unde omnisiste natus error sit voluptatem accusantium.doloremque ladantium totam rem aperieaque ipsa quae ab illo inventore.veritatis. et quasi architecto beatae vitae dicta sunt explicabo.
  # funfacts
  funfacts :
  - icon : ti-server # themify icon pack : https://themify.me/themify-icons
    title : Projects Done
    count : 230
    
  - icon : ti-face-smile # themify icon pack : https://themify.me/themify-icons
    title : Satisfied Clients
    count : 789
    
  - icon : ti-thumb-up # themify icon pack : https://themify.me/themify-icons
    title : Cup Of Coffee
    count : 580

  # progressbar
  progressbar : 
  - title : Branding
    progress : 85%
    
  - title : Consulting
    progress : 90%
    
  - title : Business
    progress : 75%
    
  - title : Promotion
    progress : 90%
      
########################################## project ####################################
project:
  enable : false
  title: "Latest Projects"
  subtitle: "Our Works"
  section: "project" # showing items from project section
  # project item comes from "content/project" folder

########################################### Mission ###################################
mission:
  enable : false
  subtitle : Our Goal
  title : Company Mission
  content : Lorem ipsum dolor sit amet consectetur adipisicing elit sed eiusmod tempor didunt laboris nisi ut aliquip ex ea commodo consequat.
  image : images/chart.png
  accordion:
  - title : Our Company Mission
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.
    
  - title : Our Company Vision
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.
    
  - title : Our Company Goal
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.

##################################### Promo video ####################################
promo_video:
  enable : false
  title : "We Are Alawys <br> Comited"
  bg_image : "images/background/promo-video.jpg"
  video_URL : "https://www.youtube.com/embed/ResipmZmpDU"
  video_title : "Lorem ipsum dolor <br> sit amet con."

##################################### call to action #################################
testimonial:
  enable : false
  subtitle : Clients
  title : What client Say
  image : images/client.png
  testimonial_item :
  - name : Julia Robertson
    content : Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
    designation : Happy Clients
    
  - name : Julia Robertson
    content : Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
    designation : Happy Clients
    
  - name : Julia Robertson
    content : Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
    designation : Happy Clients

##################################### call to action #################################
call_to_action:
  enable : true
  bg_image : "images/background/cta.jpg"
  title : "Trust TB Pro Invest for all your investment inquiries."
  button:
    enable : true
    label : "get a quote"
    link : "contact/"
      
########################################## blog ####################################
blog:
  enable : false
  title: "Company News"
  subtitle: "Latest News"
  section: "news"
  # blog item comes from "content/blog" folder
  
################################ clints logo slider ################################
clients_logo_slider:
  enable : false
  client_logos:
  - logo: "images/client-logo/client-logo-1.png"
    link: "#"

  - logo: "images/client-logo/client-logo-2.png"
    link: "https://examplesite.com"

  - logo: "images/client-logo/client-logo-3.png"
    link: "#"

  - logo: "images/client-logo/client-logo-4.png"
    link: "https://examplesite.com"

  - logo: "images/client-logo/client-logo-5.png"
    link: "#"

  - logo: "images/client-logo/client-logo-3.png"
    link: "https://examplesite.com"

    
---