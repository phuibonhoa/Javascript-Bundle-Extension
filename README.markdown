#Javascript Extension TextMate Bundle

##Description

This bundle is meant to extend the javascript bundle that comes with Textmate and mainly adds JQuery support but also adds other javascript helpers.  Installing this bundle will not conflict with the default Javascript bundle; they should work hand-in-hand.

####Changes
 * <code>docready⇥</code> $(document).ready(function(){ ...
 * <code>con⇥</code> console.log()
 * <code>func⇥</code> function(){ ...
 * <code>$⇥</code> $("")
 * Typing <code>$</code> with text selected automatically inserts text inside $("")
 * Lots more!
 
##Installation

1. $ `cd ~/Library/Application\ Support/TextMate/Bundles/`
2. $ `git clone git://github.com/phuibonhoa/Javascript-Bundle-Extension.git JavascriptExtension.tmbundle`
3. $ `osascript -e 'tell app "TextMate" to reload bundles'`

If you'd like to install all my bundles, check out this [script](http://gist.github.com/443129) written by [mkdynamic](http://github.com/mkdynamic).  It installs all bundles and backups any existing bundles with conflicting names.  Thanks Mark!

##My Other Textmate Bundles
My bundles work best when use in conjunction with my other bundles:

 * Rails - [http://github.com/phuibonhoa/ruby-on-rails-tmbundle](http://github.com/phuibonhoa/ruby-on-rails-tmbundle)
 * Ruby - [http://github.com/phuibonhoa/ruby-tmbundle](http://github.com/phuibonhoa/ruby-tmbundle)
 * Shoulda - [http://github.com/phuibonhoa/ruby-shoulda-tmbundle](http://github.com/phuibonhoa/ruby-shoulda-tmbundle)
 * HAML - [http://github.com/phuibonhoa/handcrafted-haml-textmate-bundle](http://github.com/phuibonhoa/handcrafted-haml-textmate-bundle)
 * Sass - [http://github.com/phuibonhoa/ruby-sass-tmbundle](http://github.com/phuibonhoa/ruby-sass-tmbundle)
 * JavaScript - [http://github.com/phuibonhoa/Javascript-Bundle-Extension](http://github.com/phuibonhoa/Javascript-Bundle-Extension)
 * CTags - [http://github.com/phuibonhoa/tm-ctags-tmbundle](http://github.com/phuibonhoa/tm-ctags-tmbundle)

##Credits

![BookRenter.com Logo](http://assets0.bookrenter.com/images/header/bookrenter_logo.gif "BookRenter.com")

Written by [Philippe Huibonhoa](http://github.com/phuibonhoa) and funded by [BookRenter.com](http://www.bookrenter.com "BookRenter.com").
