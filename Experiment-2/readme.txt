Name:-Mahima Naik 

Date of experiment:-27/11/2024

Python version used:-Python 3.11.3

Flask version used:-Flask 3.1.0

Werkzeug version used:-Werkzeug 3.1.3

Issues encountered:-In displaying curl command outputs (GET, POST, and notfound endpoints)

Resolution:-Adding a route for root(/):
                    @app.route('/')
                    def home():
                    	return jsonify(message="Welcome to the Flask API!"), 200