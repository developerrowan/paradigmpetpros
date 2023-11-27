<div class="row">
  <div class="col-xs-12 col-lg-4" />
  <div class="col-xs-12 col-lg-4">
    <form>
      <div class="mb-3">
        <label for="txtName" class="form-label">Name</label>
        <input
          type="text"
          class="form-control"
          id="txtName"
          placeholder="Name"
          required
          aria-required="true"
        />
      </div>
      <div class="mb-3">
        <label for="txtPhone" class="form-label">Phone number</label>
        <input
          type="tel"
          class="form-control"
          id="txtPhone"
          placeholder="(123) 456-7890"
          required
          aria-required="true"
        />
      </div>
      <div class="mb-3">
        <label for="txtEmail" class="form-label">Email address</label>
        <input
          type="email"
          class="form-control"
          id="txtEmail"
          placeholder="name@example.com"
          required
          aria-required="true"
        />
      </div>
      <div class="mb-3">
        <label for="optTimezone" class="form-label">Time zone</label>
        <select
          class="form-select"
          id="optTimezone"
          aria-label="Pet type"
          required
          aria-required="true"
        >
          <option selected>Select your time zone</option>
          <option value="hst">Hawaii Standard Time (Honolulu, HI)</option>
          <option value="akst">Alaska Standard Time (Anchorage, AK)</option>
          <option value="pst">Pacific Standard Time (Los Angeles, CA)</option>
          <option value="mst">Mountain Standard Time (Salt Lake City, UT)</option>
          <option value="cst">Central Standard Time (Chicago, IL)</option>
          <option value="est">Eastern Standard Time (New York City, NY)</option>
        </select>
      </div>
      <div class="mb-3">
        <label for="txtPetName" class="form-label">Pet's name</label>
        <input
          type="text"
          class="form-control"
          id="txtPetName"
          placeholder="Good Boy"
          required
          aria-required="true"
        />
      </div>
      <div class="mb-3">
        <label for="numPetAge" class="form-label">Pet's age</label>
        <input
          type="number"
          class="form-control"
          id="numPetAge"
          placeholder="1"
          min="0"
          max="100"
          required
          aria-required="true"
        />
      </div>
      <div class="mb-3">
        <label for="optPetType" class="form-label">Pet type</label>
        <select
          class="form-select"
          id="optPetType"
          aria-label="Pet type"
          required
          aria-required="true"
        >
          <option selected>Select what kind of pet you have</option>
          <option value="cat">Cat</option>
          <option value="dog">Dog</option>
          <option value="bird">Bird</option>
          <option value="fish">Fish</option>
          <option value="smallanimal">Small animal</option>
          <option value="other">Other</option>
        </select>
      </div>
      <div class="mb-3">
        <button class="btn btn-primary" type="submit">Request consulation</button>
      </div>
    </form>
  </div>
  <div class="col-xs-12 col-lg-4" />
</div>
