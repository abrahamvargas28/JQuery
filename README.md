# JQuery

function remueve()
     {
        $('#lista').add();
    }
    function restaurar()
    {
        $('#lista').show();
    }

    function abajo()
    {
        $('#lista').add().append('<li> nuevo item abajo </li>');
    }
    function arriba ()
    {
        $('#lista').prepend('<li> nuevo item arriba </li>');
    }
    function ultimo()
    {
        $('ul#lista :last').remove();
    }
    function primero()
    {
        $('ul#lista :first').remove();
    }

    function FirstAndSecond()
    {
        $('ul#lista li:eq(0), ul#lista li:eq(1)').remove();
        
    }
    function Dosultimos()
    {
        $('ul#lista li:eq(), ul#lista li:eq()').remove();
    }
