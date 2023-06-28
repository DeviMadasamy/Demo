/**
 * Created by benoti on 25/08/2016.
 */

jQuery(document).ready(function ($) {


    $('body').append('<a href="#" class="scrollTop" style="display:none;"></a>');
    //Check to see if the window is top if not then display button
    $(window).scroll(function(){
        if ($(this).scrollTop() > 100) {
            $('.scrollTop').fadeIn();
        } else {
            $('.scrollTop').fadeOut();
        }
    });

    // Click event to scroll to top (swing, linear)
    $('.scrollTop').click(function(){

        var speed = scrolltopEffect.speed;
        var effectType = scrolltopEffect.type;

        $('html, body').animate({scrollTop : 0}, speed, effectType);
        return false;
    });

});