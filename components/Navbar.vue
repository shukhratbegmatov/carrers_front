<template>
<div class="top-menu sticky-container" style="background: transparent;">
  <div class="small-12 sticky">
    <div class="top-menu__main ">
      <div class="top-menu__left">
        <ul class="top-menu__logo">
          <!--We need svg image-->
          <li><a href="/"><img alt="CareerHunter" class="top-menu__image" width="129" height="25" src="//cdn1.careerhunter.io/assets/CareerHunter-c5d37d4480b8e9fd358ce4d6f1fe629893627bf89acf827c9c68f5fde015b306.svg"></a></li>
        </ul>
      </div>
      <div class="top-menu__right">
        <nav role="navigation">
          <ul class="top-menu__list" >
            <li itemprop="name" class=""><a class="top-menu__option"  href="/tests">Tests</a></li>
            <li itemprop="name" class=""><a class="top-menu__option"  href="/jobs">Jobs</a></li>
            <li itemprop="name">
            <div data-react-class="buttons/getStartedMenuButton" data-react-props="{&quot;user&quot;:null,&quot;deleted&quot;:null,&quot;upgrade_page&quot;:false}" data-react-cache-id="buttons/getStartedMenuButton-0">
              <NuxtLink to="/auth/login" class="button button--green before-fade-in fade-in" >
               <span class="hideText">Login</span>
                  <span class="button__hovered" style="top: 34px; left: 73.9219px;"></span>
               </NuxtLink>
               </div>
            </li>
            <!-- <li class="top-menu__item   ">
              <div class="hamburger button button--grey" id="toggle-menu">
                <span class="button__hovered" style="top: 35px; left: 33.5px;"></span>
                <span class="hamburger__part hamburger__part--top"></span>
                <span class="hamburger__part hamburger__part--middle"></span>
                <span class="hamburger__part hamburger__part--bottom"></span>
              </div>
            </li> -->
          </ul>
        </nav>
      </div>
    </div>
  </div>
</div>
</template>