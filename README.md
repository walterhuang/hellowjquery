    <script type="text/javascript">
        $(document).ready(function () {
            $(':input').each(function() {
                var elem = $(this);
                alert(elem.val('Foo'));
            });
            
        });
    </script>
