# Paypal
echo "# Paypal" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sankarsmith/paypal.git
git push -u origin master





Paypal Payment Intergration Method for Web-based Payment process.

# Steps

1.Make a form submit to the payments.php file with the values like amount biller email etc..(index.html)

2.Then it goes to the payments.php file and Then it that page we need to configure the receiver emailID and urls.

3.After the success payment, it goes to the notify_url and insert records into Database and then It redirects to Success page and if fails means failure page.

4.Thats all..
