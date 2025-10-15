FROM nginx:1.25-alpine

# Copy all files
COPY frontend/ /usr/share/nginx/html

# Rename Devops_Intern.html to index.html
RUN mv /usr/share/nginx/html/Devops_Intern.html /usr/share/nginx/html/index.html

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
