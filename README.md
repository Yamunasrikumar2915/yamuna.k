<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Student Details • Sree Abiraami ASCW</title>
  <style>
    :root { font-family: system-ui, Arial, sans-serif; }
    body { margin: 0; min-height: 100dvh; display: grid; place-items: center; background: #f6f7fb; }
    form { width: min(420px, 92vw); background: #fff; padding: 22px; border-radius: 14px; box-shadow: 0 8px 24px rgba(0,0,0,.08); }
    h1 { font-size: 1.1rem; margin: 0 0 14px; }
    .row { display: grid; gap: 8px; margin: 10px 0 14px; }
    label { font-size: .9rem; color: #222; }
    input, select, button {
      width: 100%; padding: 10px 12px; border: 1px solid #dcdde3; border-radius: 10px; font-size: 1rem;
    }
    input:focus, select:focus { outline: none; border-color: #6a7cff; box-shadow: 0 0 0 3px rgba(106,124,255,.15); }
    button { cursor: pointer; background: #6a7cff; color: #fff; border: none; font-weight: 600; }
    small { color: #666; }
    .note { font-size: .85rem; color: #444; margin-top: 6px; }
  </style>
</head>
<body>
  <form onsubmit="event.preventDefault(); alert('Submitted ✅'); this.reset();">
    <h1>Student Details (Sree Abiraami Arts & Science College for Women)</h1>

    <div class="row">
      <label for="name">Full Name</label>
      <input id="name" name="name" type="text" placeholder="Yamunasri K R" required
             autocomplete="name" />
    </div>

    <div class="row">
      <label for="email">College Email</label>
      <input id="email" name="email" type="email" placeholder="yamunasri.kr@abiraami.edu.in" required
             autocomplete="email" />
      <small>Use your college email ID.</small>
    </div>

    <div class="row">
      <label for="year">Year</label>
      <select id="year" name="year" required>
        <option value="" selected disabled>Choose your year</option>
        <option>1st Year</option>
        <option selected>2nd Year</option>
        <option>3rd Year</option>
      </select>
    </div>

    <div class="row">
      <label for="dept">Department</label>
      <input id="dep
