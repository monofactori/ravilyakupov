<script>
	import '../app.pcss';
	import { AppShell } from '@skeletonlabs/skeleton';
</script>

<div class="app">
	<AppShell>
		<!-- (header) -->
		<!-- (sidebarRight) -->
		<!-- (pageHeader) -->
		<!-- Router Slot -->
		<slot />
		<!-- ---- / ---- -->
		<!-- (pageFooter) -->
		<!-- (footer) -->
	</AppShell>
</div>
