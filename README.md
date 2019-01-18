# heading one
## heading two
~~~php
$KCTHEME_Postmeta->add_meta_box( 'locations_info',
	esc_html__( 'Office Locations', 'kctheme' ), array( "{$prefix}_locations" ), '', '', 'high', array(
	'fields' => array(		
		"{$prefix}_group" => array(
			'label' => esc_html__( 'Medical Group', 'kctheme' ),
			'type'  => 'text',
			'default'  => '',
			),
		"{$prefix}_contact" => array(
			'label' => esc_html__( 'Contact No', 'kctheme' ),
			'type'  => 'text',
			'default'  => '',
			),
		
		)
	)
);

~~~

~~~css
    h1 {
        font-size: 48px;
        color: @secondaryColor;
        display: inline-block;
        margin: 0;
        line-height: 1;
        font-weight: 400;   
        text-transform: capitalize;   
        background-color: rgba(255,255,255,.5); 
        margin-bottom: 20px;
        padding: 6px 15px;
     

        @media (max-width: 991px) {
            font-size: @h1t;
            line-height: 1.2;
        }        
    }
~~~
here is single `hello.php`

```js
	 /*-------------------------------------
     Select2 activation code
     -------------------------------------*/
    if ($('select.select2').length) {
        $('select.select2').select2({
            theme: 'classic',
            dropdownAutoWidth: true,
            width: '100%'
        });
    }

    
 	$('.rt-content, .rt-sidebar').theiaStickySidebar({
		  // Settings
		  additionalMarginTop: 100
		});
	  
	/* Scroll to top */
	$('.scrollToTop').on('click',function(){
		$('html, body').animate({scrollTop : 0},800);
		return false;
	});
	$(window).scroll(function(){
		if ($(this).scrollTop() > 100) {
			$('.scrollToTop').fadeIn();
		} else {
			$('.scrollToTop').fadeOut();
		}
	});

```
