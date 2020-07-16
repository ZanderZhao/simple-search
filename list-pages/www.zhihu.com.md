# simple-search


<script src="../js/sidebar-list.js"></script>

<input id="searchInput" type="text"> <button onclick="startSearch()">Search Zhihu</button>

<script>
    function startSearch(){
       var searchEngine=new Array();
       searchEngine[0]="https://www.zhihu.com/search?type=content&q=";
       searchEngine[1]="https://www.google.com/search?q=";
       searchEngine[2]="https://bing.com/search?q=";
       var defaultSearchEngine=searchEngine[0];
       var searchValue = document.getElementById("searchInput").value;
       window.open(defaultSearchEngine+searchValue);
    }
</script>


