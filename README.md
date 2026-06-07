# cancuntravelsolutions-mx.github.io
We provide Airport Ground Transportation to and from hotels in Cancun, Costa Mujeres, Playa Mujeres, Playa del Carmen, Tulum and Riviera Maya as tours. We can arrange from small families to large groups, Luxury Corporate Retreats, Incentives Groups, Weddings, and Large Custom Events
<form id="transfer-tour-booking-form">
  <!-- Contact Info -->
  <label>Full Name:</label>
  <input type="text" name="client_name" required>

  <!-- Trip Logistics -->
  <label>Arrival Date:</label>
  <input type="date" name="arrival_date" required>
  <label>Departure Date:</label>
  <input type="date" name="departure_date">

  <label>Airport / Terminal:</label>
  <input type="text" name="airport" placeholder="e.g., JFK, CUN" required>

  <label>Amount of People:</label>
  <input type="number" name="passengers" min="1" required>

  <!-- Trip Type Routing -->
  <label>Trip Type:</label>
  <select name="trip_type" required>
    <option value="round_trip">Round Trip</option>
    <option value="one_way">One Way</option>
  </select>

  <!-- Service Tiers -->
  <label>Transfer Tier:</label>
  <select name="transfer_tier" required>
    <option value="regular_private">Regular Private Transfer</option>
    <option value="deluxe_private">Deluxe Private Transfer</option>
  </select>

  <!-- Add-on Selections -->
  <fieldset>
    <legend>Select Tours & Add-ons:</legend>
    <input type="checkbox" id="tour1" name="tours" value="city_tour">
    <label for="tour1">Historical City Tour</label><br>
    <input type="checkbox" id="tour2" name="tours" value="adventure_tour">
    <label for="tour2">Deluxe Adventure Tour</label>
  </fieldset>

  <button type="submit">Proceed to Payment</button>
</form>
https://github.com/mybooking-es/mybooking-web-sample-html-bootstrap.git
