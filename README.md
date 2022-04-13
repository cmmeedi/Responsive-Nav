# Responsive-Nav
A responsive nav using Flex and Media Queries

                    Media-Queries

Rules can be set for certain sizes of a screen.  by using 

@media(width: 480px){
    background-color: white;
}

The 'background-color' will now change when the size of the screen is exactly at 480 pixels wide.  

It is more common to use 'min-width' and 'max-width'. 
by doing something like

@media(min-width: 480px) and (max-width: 720px){
    background-color: white;
}

@media(min-width: 720px) and (max-width: 1080){
    background-color: orange;
}

The site will change color according to how big someone resizes their window on their machine.  
This should be used to develop with the "Mobile First" technique making a website for mobile devices and then altering it with the media querie to adjust for tablets then PCs and Laptops.  
Another piece to consider is 

@media(orientation: landscape){
    background-color: yellow;
}

'media-queries' should be used in junction with 'flex-box' to make a fluid and smooth responsive webpage.

The chrome devTools offer different mobile device views that can be used to help build within these dimensions and even show the dimensions at the top of the page when choosing different devices

most devices are a bit bigger then 400 so 380px would be a good place to start for mobile
