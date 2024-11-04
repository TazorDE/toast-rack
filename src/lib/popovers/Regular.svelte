<button class="btn preset-filled-primary-500" popovertarget="regular"> Open regular toast </button>
<!-- Regular toast -->
<div
	class="animate__animated animate__backInDown relative m-2 w-1/3 rounded-xl bg-surface-900 p-4 text-white"
	id="regular"
	popover="manual"
>
	<button
		class="float-end flex size-6 items-center justify-center rounded border border-error-700"
		popovertarget="regular"
		popovertargetaction="hide"
	>
		<span class="font-bold" aria-hidden="true">X</span>
		<span class="sr-only">close</span>
	</button>
	<p class="font-bold">This is a regular toast message</p>
</div>
