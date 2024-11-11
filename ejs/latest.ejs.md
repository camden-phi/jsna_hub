```{=html}
<% for (const item of items) { %>
  <a href="<%- item.path %>" style="font-weight: bold; text-decoration: none; border-bottom: 1px solid #522E91; color: #522E91"><%= item.title %></a>
    </br>
    </br>
<% } %>
```
