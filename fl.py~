from flask import Flask, request, session, g, redirect, url_for, abort, render_template, flash
app=Flask(__name__)
@app.route("/home")
def home():
	return render_template('home.html')

@app.route("/aboutme")
def aboutme():
	return render_template('aboutme.html')

@app.route("/contactme")
def contactme():
	return render_template('contactme.html')




if __name__ == "__main__":
	app.debug = True
	app.run()

