--- 
title: Home
is_hidden: true
---

# Posts

<% articles.each do |article| %>
  <%= link_to(article[:title], article) %> - <%= pretty_time(article[:created_at]) %>
<% end %>
