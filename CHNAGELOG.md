#Change Log
Version 1.1.2 *(2015-10-14)*
----------------------------
* add method setViewPager(ViewPager vp, String[] titles)  for the condition that you do not want set titles in page adapter 

Version 1.1.4 *(2015-10-16)*
----------------------------
* fix bug: indicator not show if you do not call viewpager's setCurrentItem method during initialization.

Version 1.1.6 *(2015-10-18)*
----------------------------
* add method setViewPager(ViewPager vp, String[] titles, FragmentActivity fa, ArrayList<Fragment> fragments)
  for the condition that you even do not want to instantiate page adapter by yourself
* add listener OnTabSelectedListener

Version 1.1.8 *(2015-10-19)*
----------------------------
* add block indicator

Version 1.2.0 *(2015-10-20)*
----------------------------
* add unread msg dot (TipView)

Version 1.3.0 *(2015-10-22)*
----------------------------
* new added View: CommonTabLayout is a tablayout without dependence of ViewPager

Version 1.3.2 *(2015-10-28)*
----------------------------
* extract common attributes

Version 1.3.4 *(2015-11-5)*
----------------------------
* replace TipView with RoundTextView