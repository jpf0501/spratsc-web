<svelte:head>
    <title>SPRATSC Web Database System</title>
</svelte:head>

<div class="hero min-h-screen bg-base-200">
    <div class="hero-content flex-col">
      <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100">
        <div class="card-body">
          <div class="form-control">
            <!-- svelte-ignore a11y-label-has-associated-control -->
            <label class="label">
              <span class="label-text">Email</span>
            </label>
            <input type="text" placeholder="Email" class="input input-bordered my-2" />
          </div>
          <div class="form-control">
            <!-- svelte-ignore a11y-label-has-associated-control -->
            <label class="label">
              <span class="label-text">Password</span>
            </label>
            <input type="password" placeholder="Password" class="input input-bordered my-2" />
          </div>
          <div class="form-control mt-6">
            <button class="btn btn-primary">Login</button>
          </div>
        </div>
      </div>
    </div>
  </div>