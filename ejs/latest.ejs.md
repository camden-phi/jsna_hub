```{=html}
<% for (const item of items) { %>
  <a href="<%- item.path %>"><b><%= item.title %></b> <i><small>(<%= item.date %>)</i></small></a>
    </br><p></p>
<% } %>
```
