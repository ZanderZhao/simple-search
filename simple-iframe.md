
<p><a href="list-pages/bing.com">必应</a>  <a href="list-pages/www.google.com">谷歌</a>  <a href="list-pages/www.baidu.com">百度</a>  <a href="list-pages/en.wikipedia.org">维基</a>  <a href="menu">更多</a></p>

<input id="searchInput" type="text"> <button onclick="startSearch()">百度搜索</button>

<script>
    function startSearch(){
       var searchEngine=new Array();
       searchEngine[0]="https://www.baidu.com/s?wd=";
       searchEngine[1]="https://www.google.com/search?q=";
       searchEngine[2]="https://bing.com/search?q=";
       searchEngine[3]="https://www.so.com/s?q=";
       searchEngine[4]="https://www.sogou.com/web?query=";
       searchEngine[5]="https://en.wikipedia.org/w/index.php?search=";
       searchEngine[6]="https://www.zhihu.com/search?type=content&q=";
       searchEngine[7]="https://weixin.sogou.com/weixin?type=2&query=";
       searchEngine[8]="https://s.weibo.com/weibo?q=";
       searchEngine[9]="https://www.douban.com/search?q=";
       searchEngine[10]="https://zzk.cnblogs.com/s?t=b&w=";
       searchEngine[11]="https://stackoverflow.com/search?q=";
       searchEngine[12]="https://so.csdn.net/so/search/s.do?q=";
       searchEngine[13]="https://github.com/search?q=";
       searchEngine[14]="https://www.ecosia.org/search?q=";
       searchEngine[15]="https://www.jianshu.com/search?q=";
       searchEngine[16]="https://segmentfault.com/search?q=";
       searchEngine[17]="https://search.gitee.com/?skin=rec&type=repository&q=";
       var defaultSearchEngine=searchEngine[0];
       var searchValue = document.getElementById("searchInput").value;
       window.open(defaultSearchEngine+searchValue);
    }
</script>


