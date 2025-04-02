# Changing XAMPP Port to 8080

To change XAMPP's default port from 80 to 8080, you'll need to modify the Apache configuration files directly in your XAMPP installation. This cannot be done through the application files alone.

Follow these steps:
1. Open XAMPP Control Panel
2. Click on "Config" button for Apache
3. Select "httpd.conf"
4. Find the lines:
   ```
   Listen 80
   ServerName localhost:80
   ```
5. Change them to:
   ```
   Listen 8080
   ServerName localhost:8080
   ```
6. Save the file and restart Apache through XAMPP Control Panel

Note: This change needs to be made in your XAMPP installation directory, typically found at:
- Windows: `C:\xampp\apache\conf\httpd.conf`
- Linux: `/opt/lampp/apache2/conf/httpd.conf`
- macOS: `/Applications/XAMPP/xamppfiles/apache2/conf/httpd.conf`