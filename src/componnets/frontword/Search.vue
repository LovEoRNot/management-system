<template>
  <div class="search-bar">
    <h2><em>SEARCH</em></h2>
    <hr />
    <div class="search-input">
      <i class="expand-icon"></i>
      <input type="text" class="input" id="searchInput"/>
      <button type="button" id="submit">搜索</button>
    </div>	
    <div class="search-option">
      <ul>
        <li class="list">查询方式：</li>
        <li class="list">
          <input type="radio" name="option" id="book-title" value="bookname" checked="checked"/>
          <label for="book-title"> 书名</label>
        </li>
        <li class="list">
          <input type="radio" name="option" id="book-ISBN" value="ISBN"/>
          <label for="book-ISBN"> ISBN</label>
        </li>
        <li class="list">
          <input type="radio" name="option" id="author" value="author"/>
          <label for="author"> 作者</label>
        </li>
        <li class="list">
          <input type="radio" name="option" id="pubname" value="pubname"/>
          <label for="pubname"> 出版社</label>
        </li>
      </ul>
    </div>
    <hr />
    <div class="content">
      <aside>				
        <h3>热度排行</h3>
        <ul>
        <!-- <c:forEach items="${hotBook.dataList }" var="book">
          <li>${book.bookname }</li>
        </c:forEach>						 -->
        </ul>
      </aside>
      <table class="table table-hover table-responsive">
        <thead>
          <tr>
            <th>序号</th>
            <th>书名</th>
            <th>ISBN</th>
            <th>作者</th>
            <th>出版社</th>
            <th>可借数量</th>		
          </tr>			
        </thead>
        <tbody id="infoShow">
        </tbody>
      </table>			
    </div>			
  </div>
</template>

<script>
  
</script>
