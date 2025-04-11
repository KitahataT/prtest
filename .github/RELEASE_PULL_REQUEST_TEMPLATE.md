<%= ENV['PR_TITLE'] %>

## 変更PR
<% pull_requests.each do |pr| -%>
- [ ] #<%= pr.number %> @<%= pr.author %>
<% end -%> 
- ああああ