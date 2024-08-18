<template>
  <div>
    <div class="bg-light rounded p-5">
      <p class="d-inline-block border rounded-pill py-1 px-4">Tele consultation</p>
      <h1 class="mb-4">Symptom checker</h1>
      <form>
        <div class="row g-3">
          <div class="col-md-6">
            <div class="form-floating">
              <input type="number" class="form-control" id="name" placeholder="Your Hyperthemic (Celicus)" />
              <label for="name">Your Hyperthemic</label>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-floating">
              <input type="number" class="form-control" id="email" placeholder="Your Resmisubery rate (Celicus)" />
              <label for="email">Your Resmisubery rate</label>
            </div>
          </div>
          <div class="col-12">
            <div class="form-floating">
              <input type="number" class="form-control" id="subject" placeholder="Pulse rate ( percentic)" />
              <label for="subject">Pulse rate</label>
            </div>
          </div>
          <div class="col-12">
            <div class="form-floating">
              <select name="consicuous" id="subject" class="form-control">
                <option selected>Consciousness</option>
                <option value="">lethargy/malcuise</option>
                <option value="">Comal/unconscious</option>
              </select>
            </div>
          </div>
          
          <div class="col-12">
            <div class="form-floating">
              <select name="consicuous" class="form-control">
                <option value="">pculor_cyanosis</option>                
              </select>
            </div>
          </div>

          <div class="col-12">
            <div class="form-floating">
              <textarea
                class="form-control"
                placeholder="Any thing more you want to tell us (Optional)"
                id="message"
                style="height: 100px"
              ></textarea>
              <label for="message">Other Information (Any thing more you want to tell us (Optional))</label>
            </div>
          </div>
          <div class="col-12">
            <button class="btn btn-primary w-100 py-3" type="submit">Send Message</button>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TeleMedicine'
}
</script>
