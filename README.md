!DOCTYPE html
html lang=en
head
  meta charset=UTF-8
  meta name=viewport content=width=device-width, initial-scale=1.0
  titleYork Web Creations - Professional Web Design Agencytitle
  meta name=description content=Professional web design for small businesses. Fast delivery, stunning results.
  link rel=stylesheet href=httpscdnjs.cloudflare.comajaxlibsfont-awesome6.4.0cssall.min.css
  link href=httpsfonts.googleapis.comcss2family=Poppinswght@400;500;600;700&display=swap rel=stylesheet
  script src=httpscdn.tailwindcss.comscript
  style
    body { font-family 'Poppins', sans-serif; }
    @keyframes blob {
      0%, 100% { transform translate(0, 0) scale(1); }
      33% { transform translate(30px, -50px) scale(1.1); }
      66% { transform translate(-20px, 20px) scale(0.9); }
    }
    @keyframes fade-in-down {
      from { opacity 0; transform translateY(-20px); }
      to { opacity 1; transform translateY(0); }
    }
    @keyframes fade-in-up {
      from { opacity 0; transform translateY(20px); }
      to { opacity 1; transform translateY(0); }
    }
    .animate-blob { animation blob 7s infinite; }
    .animate-fade-in-down { animation fade-in-down 0.6s ease-out; }
    .animate-fade-in-up { animation fade-in-up 0.6s ease-out; }
    .animation-delay-200 { animation-delay 0.2s; opacity 0; animation-fill-mode forwards; }
    .animation-delay-400 { animation-delay 0.4s; opacity 0; animation-fill-mode forwards; }
    .animation-delay-600 { animation-delay 0.6s; opacity 0; animation-fill-mode forwards; }
    .animation-delay-800 { animation-delay 0.8s; opacity 0; animation-fill-mode forwards; }
    .animation-delay-2000 { animation-delay 2s; }
    .animation-delay-4000 { animation-delay 4s; }
  style
head
body class=font-sans

  !-- HEADER --
  header class=bg-white border-b border-[#E5EDF5] sticky top-0 z-50 shadow-sm
    div class=max-w-7xl mx-auto px-4 smpx-6 lgpx-8
      div class=flex items-center justify-between h-20
        a href= class=flex items-center gap-3 group
          div class=w-12 h-12 bg-gradient-to-br from-[#4460A0] to-[#6044A0] rounded-xl flex items-center justify-center transform group-hoverrotate-6 transition-transform
            i class=fas fa-code text-white text-xli
          div
          div
            div class=text-xl font-bold text-[#1A1A1A]York Web Creationsdiv
            div class=text-xs text-[#888888]Professional Web Designdiv
          div
        a
        nav class=hidden lgflex items-center gap-8
          a href= class=text-[#1A1A1A] hovertext-[#4460A0] font-mediumHomea
          a href=our-work class=text-[#1A1A1A] hovertext-[#4460A0] font-mediumOur Worka
          a href=pricing class=text-[#1A1A1A] hovertext-[#4460A0] font-mediumPricinga
          a href=contact class=bg-[#4460A0] hoverbg-[#365080] text-white px-6 py-3 rounded-lg font-semiboldContact Usa
        nav
        button class=lghidden text-[#1A1A1A] text-2xl onclick=document.querySelector('[data-mobile-nav]').classList.toggle('hidden')
          i class=fas fa-barsi
        button
      div
    div
    div class=lghidden hidden bg-white border-t border-[#E5EDF5] data-mobile-nav
      div class=px-4 py-6 space-y-4
        a href= class=block text-[#1A1A1A] hovertext-[#4460A0] font-medium py-2Homea
        a href=our-work class=block text-[#1A1A1A] hovertext-[#4460A0] font-medium py-2Our Worka
        a href=pricing class=block text-[#1A1A1A] hovertext-[#4460A0] font-medium py-2Pricinga
        a href=contact class=block bg-[#4460A0] hoverbg-[#365080] text-white px-6 py-3 rounded-lg font-semibold text-centerContact Usa
      div
    div
  header

  !-- HERO SECTION --
  section class=relative min-h-screen flex items-center justify-center overflow-hidden bg-gradient-to-br from-[#1A1A1A] via-[#2A2A4A] to-[#4460A0]
    div class=absolute inset-0 opacity-30
      div class=absolute top-20 left-10 w-72 h-72 bg-[#4460A0] rounded-full mix-blend-multiply filter blur-3xl animate-blobdiv
      div class=absolute top-40 right-10 w-72 h-72 bg-[#A04460] rounded-full mix-blend-multiply filter blur-3xl animate-blob animation-delay-2000div
      div class=absolute bottom-20 left-12 w-72 h-72 bg-[#6044A0] rounded-full mix-blend-multiply filter blur-3xl animate-blob animation-delay-4000div
    div
    div class=relative z-10 max-w-7xl mx-auto px-4 smpx-6 lgpx-8 py-20
      div class=text-center
        div class=inline-flex items-center gap-2 bg-white10 backdrop-blur-md border border-white20 rounded-full px-6 py-2 mb-8 animate-fade-in-down
          i class=fas fa-star text-yellow-400i
          span class=text-white text-sm font-mediumProfessional Web Design Agencyspan
        div
        h1 class=text-5xl smtext-6xl lgtext-7xl font-bold text-white mb-6 animate-fade-in-up
          York Web span class=bg-gradient-to-r from-[#4460A0] via-[#6044A0] to-[#A04460] bg-clip-text text-transparentCreationsspan
        h1
        p class=text-xl smtext-2xl text-gray-300 mb-4 max-w-3xl mx-auto animate-fade-in-up animation-delay-200Stunning Websites for Small Businessesp
        p class=text-lg text-gray-400 mb-12 max-w-2xl mx-auto animate-fade-in-up animation-delay-400We transform your vision into a beautiful, functional website that drives results. Fast delivery, professional design, and unmatched quality.p
        div class=flex flex-col smflex-row gap-4 justify-center items-center animate-fade-in-up animation-delay-600
          a href=pricing class=group inline-flex items-center gap-2 bg-[#4460A0] hoverbg-[#365080] text-white px-8 py-4 rounded-lg font-semibold text-lg transition-all duration-300 transform hoverscale-105 hovershadow-2xl
            spanView Pricingspan
            i class=fas fa-arrow-right group-hovertranslate-x-1 transition-transformi
          a
          a href=our-work class=inline-flex items-center gap-2 bg-white10 backdrop-blur-md border border-white20 hoverbg-white20 text-white px-8 py-4 rounded-lg font-semibold text-lg transition-all duration-300
            i class=fas fa-eyei
            spanSee Our Workspan
          a
        div
        div class=grid grid-cols-1 smgrid-cols-3 gap-8 mt-20 animate-fade-in-up animation-delay-800
          div class=bg-white5 backdrop-blur-md border border-white10 rounded-2xl p-6 hoverbg-white10 transition-all duration-300 transform hoverscale-105
            div class=text-4xl font-bold text-white mb-2Low $div
            div class=text-gray-400Websitesdiv
          div
          div class=bg-white5 backdrop-blur-md border border-white10 rounded-2xl p-6 hoverbg-white10 transition-all duration-300 transform hoverscale-105
            div class=text-4xl font-bold text-white mb-23-7div
            div class=text-gray-400Days Deliverydiv
          div
          div class=bg-white5 backdrop-blur-md border border-white10 rounded-2xl p-6 hoverbg-white10 transition-all duration-300 transform hoverscale-105
            div class=text-4xl font-bold text-white mb-2100%div
            div class=text-gray-400Satisfactiondiv
          div
        div
      div
    div
    div class=absolute bottom-10 left-12 transform -translate-x-12 animate-bounce
      i class=fas fa-chevron-down text-white text-2xl opacity-50i
    div
  section

  !-- FEATURES SECTION --
  section class=relative bg-white py-20 lgpy-32 overflow-hidden
    div class=absolute top-0 right-0 w-96 h-96 bg-gradient-to-br from-[#4460A0]10 to-transparent rounded-full blur-3xldiv
    div class=absolute bottom-0 left-0 w-96 h-96 bg-gradient-to-tr from-[#A04460]10 to-transparent rounded-full blur-3xldiv
    div class=relative max-w-7xl mx-auto px-4 smpx-6 lgpx-8
      div class=text-center mb-16
        div class=inline-flex items-center gap-2 bg-[#E5EDF5] rounded-full px-6 py-2 mb-6
          i class=fas fa-magic text-[#4460A0]i
          span class=text-[#4460A0] text-sm font-semiboldWhy Choose Usspan
        div
        h2 class=text-4xl smtext-5xl font-bold text-[#1A1A1A] mb-6Professional Websites, span class=text-[#4460A0]Fast Deliveryspanh2
        p class=text-xl text-[#888888] max-w-2xl mx-autoWe specialize in creating beautiful, functional websites for small businesses that need a professional online presencep
      div
      div class=grid grid-cols-1 smgrid-cols-2 lggrid-cols-3 gap-8
        div class=group relative bg-gradient-to-br from-white to-[#E5EDF5] border border-[#E5EDF5] rounded-2xl p-8 hovershadow-2xl transition-all duration-500 transform hover-translate-y-2
          div class=w-16 h-16 bg-gradient-to-br from-[#4460A0] to-[#6044A0] rounded-2xl flex items-center justify-center mb-6 transform group-hoverrotate-6 transition-transform duration-300
            i class=fas fa-rocket text-white text-2xli
          div
          h3 class=text-2xl font-bold text-[#1A1A1A] mb-4Lightning Fasth3
          p class=text-[#888888] leading-relaxedGet your website delivered in just 3-7 days. No more waiting months for your online presence.p
        div
        div class=group relative bg-gradient-to-br from-white to-[#E5EDF5] border border-[#E5EDF5] rounded-2xl p-8 hovershadow-2xl transition-all duration-500 transform hover-translate-y-2
          div class=w-16 h-16 bg-gradient-to-br from-[#A04460] to-[#6044A0] rounded-2xl flex items-center justify-center mb-6 transform group-hoverrotate-6 transition-transform duration-300
            i class=fas fa-palette text-white text-2xli
          div
          h3 class=text-2xl font-bold text-[#1A1A1A] mb-4Custom Designh3
          p class=text-[#888888] leading-relaxedEvery website is uniquely crafted to match your brand and stand out from the competition.p
        div
        div class=group relative bg-gradient-to-br from-white to-[#E5EDF5] border border-[#E5EDF5] rounded-2xl p-8 hovershadow-2xl transition-all duration-500 transform hover-translate-y-2
          div class=w-16 h-16 bg-gradient-to-br from-[#44A060] to-[#6044A0] rounded-2xl flex items-center justify-center mb-6 transform group-hoverrotate-6 transition-transform duration-300
            i class=fas fa-mobile-alt text-white text-2xli
          div
          h3 class=text-2xl font-bold text-[#1A1A1A] mb-4Mobile Optimizedh3
          p class=text-[#888888] leading-relaxedYour site will look perfect on every device - phones, tablets, and desktops.p
        div
        div class=group relative bg-gradient-to-br from-white to-[#E5EDF5] border border-[#E5EDF5] rounded-2xl p-8 hovershadow-2xl transition-all duration-500 transform hover-translate-y-2
          div class=w-16 h-16 bg-gradient-to-br from-[#6044A0] to-[#4460A0] rounded-2xl flex items-center justify-center mb-6 transform group-hoverrotate-6 transition-transform duration-300
            i class=fas fa-dollar-sign text-white text-2xli
          div
          h3 class=text-2xl font-bold text-[#1A1A1A] mb-4Affordable Pricingh3
          p class=text-[#888888] leading-relaxedStarting at just $399.99, get professional quality without breaking the bank.p
        div
        div class=group relative bg-gradient-to-br from-white to-[#E5EDF5] border border-[#E5EDF5] rounded-2xl p-8 hovershadow-2xl transition-all duration-500 transform hover-translate-y-2
          div class=w-16 h-16 bg-gradient-to-br from-[#A06044] to-[#A04460] rounded-2xl flex items-center justify-center mb-6 transform group-hoverrotate-6 transition-transform duration-300
            i class=fas fa-search text-white text-2xli
          div
          h3 class=text-2xl font-bold text-[#1A1A1A] mb-4SEO Optimizedh3
          p class=text-[#888888] leading-relaxedBuilt with best practices to help your business get found on search engines.p
        div
        div class=group relative bg-gradient-to-br from-white to-[#E5EDF5] border border-[#E5EDF5] rounded-2xl p-8 hovershadow-2xl transition-all duration-500 transform hover-translate-y-2
          div class=w-16 h-16 bg-gradient-to-br from-[#4460A0] to-[#44A060] rounded-2xl flex items-center justify-center mb-6 transform group-hoverrotate-6 transition-transform duration-300
            i class=fas fa-headset text-white text-2xli
          div
          h3 class=text-2xl font-bold text-[#1A1A1A] mb-4Ongoing Supporth3
          p class=text-[#888888] leading-relaxedWe're here to help even after launch. Your success is our success.p
        div
      div
    div
  section

  !-- CTA SECTION --
  section class=relative bg-gradient-to-br from-[#4460A0] to-[#6044A0] py-20 overflow-hidden
    div class=absolute inset-0 opacity-10
      div class=absolute top-0 left-0 w-full h-full style=background-image repeating-linear-gradient(45deg, transparent, transparent 35px, rgba(255,255,255,.05) 35px, rgba(255,255,255,.05) 70px);div
    div
    div class=relative max-w-6xl mx-auto px-4 smpx-6 lgpx-8 text-center
      div class=bg-white10 backdrop-blur-lg border border-white20 rounded-3xl p-12 smp-16 transform hoverscale-105 transition-transform duration-500
        i class=fas fa-quote-left text-white30 text-4xl mb-6i
        h2 class=text-3xl smtext-4xl lgtext-5xl font-bold text-white mb-8 leading-tightReady to Transform Your Online Presenceh2
        p class=text-xl text-white90 mb-10 max-w-3xl mx-autoJoin dozens of satisfied small business owners who've elevated their brand with a professional website from York Web Creationsp
        div class=flex flex-col smflex-row gap-4 justify-center items-center
          a href=contact class=group inline-flex items-center gap-2 bg-white text-[#4460A0] px-8 py-4 rounded-lg font-bold text-lg hoverbg-[#E5EDF5] transition-all duration-300 transform hoverscale-105 hovershadow-2xl
            i class=fas fa-commentsi
            spanGet Started Todayspan
            i class=fas fa-arrow-right group-hovertranslate-x-1 transition-transformi
          a
          a href=pricing class=inline-flex items-center gap-2 bg-white10 backdrop-blur-md border-2 border-white text-white px-8 py-4 rounded-lg font-bold text-lg hoverbg-white20 transition-all duration-300
            i class=fas fa-tagi
            spanView Pricingspan
          a
        div
        div class=mt-12 pt-8 border-t border-white20
          div class=flex flex-wrap justify-center items-center gap-8 text-white80
            div class=flex items-center gap-2i class=fas fa-check-circle text-[#44A060]ispanNo Hidden Feesspandiv
            div class=flex items-center gap-2i class=fas fa-check-circle text-[#44A060]ispanFast Deliveryspandiv
            div class=flex items-center gap-2i class=fas fa-check-circle text-[#44A060]ispan100% Satisfactionspandiv
          div
        div
      div
    div
  section

  !-- FOOTER --
  footer class=bg-[#1A1A1A] text-white py-16
    div class=max-w-7xl mx-auto px-4 smpx-6 lgpx-8
      div class=grid grid-cols-1 smgrid-cols-2 lggrid-cols-4 gap-8 mb-12
        div
          div class=flex items-center gap-3 mb-4
            div class=w-10 h-10 bg-gradient-to-br from-[#4460A0] to-[#6044A0] rounded-lg flex items-center justify-center
              i class=fas fa-code text-whitei
            div
            div class=text-lg font-boldYork Web Creationsdiv
          div
          p class=text-gray-400 text-sm leading-relaxedProfessional web design for small businesses. Fast delivery, stunning results.p
        div
        div
          h3 class=font-bold text-lg mb-4Quick Linksh3
          ul class=space-y-2
            lia href= class=text-gray-400 hovertext-white transition-colorsHomeali
            lia href=our-work class=text-gray-400 hovertext-white transition-colorsOur Workali
            lia href=pricing class=text-gray-400 hovertext-white transition-colorsPricingali
            lia href=contact class=text-gray-400 hovertext-white transition-colorsContactali
          ul
        div
        div
          h3 class=font-bold text-lg mb-4Servicesh3
          ul class=space-y-2 text-gray-400
            liWeb Designli
            liMobile Optimizationli
            liSEO Servicesli
            liWebsite Maintenanceli
          ul
        div
        div
          h3 class=font-bold text-lg mb-4Contacth3
          ul class=space-y-3
            li
              a href=sms410-762-9757 class=flex items-center gap-2 text-gray-400 hovertext-white transition-colors
                i class=fas fa-mobile-alt text-[#44A060]i
                span(410) 762-9757span
              a
            li
            li
              a href=mailtokaythomasq7@gmail.com class=flex items-center gap-2 text-gray-400 hovertext-white transition-colors
                i class=fas fa-envelope text-[#4460A0]i
                span class=text-smkaythomasq7@gmail.comspan
              a
            li
          ul
        div
      div
      div class=pt-8 border-t border-gray-800
        div class=flex flex-col smflex-row items-center justify-between gap-4
          p class=text-gray-400 text-sm© 2024 York Web Creations. All rights reserved.p
          div class=flex items-center gap-4
            a href=# class=text-gray-400 hovertext-white transition-colorsPrivacy Policya
            span class=text-gray-600span
            a href=# class=text-gray-400 hovertext-white transition-colorsTerms of Servicea
          div
        div
      div
    div
  footer

body
html
