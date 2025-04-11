【Staging】ReleasePR <%= Time.now %>
## 変更PR
<% pull_requests.each do |pr| -%>
<%=  pr.to_checklist_item %>
<% end -%>
