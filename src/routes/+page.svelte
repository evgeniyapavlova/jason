<script>
	import AllBlocksTH from '$comps/AllBlocksTH.svelte';
	import meta_img from '$lib/images/meta__img__en.jpg';

	const title = 'วิธีใช้ระบบเพื่อดึงกำไรจากตลาด';
	const desc =
		'การฝึกอบรมฟรีสำหรับนักเทรดที่มีความตั้งใจ - ทำไมวิธีการทางระบบถึงเป็นทางเลือกที่ดีที่สุดในการทำเงินจากตลาด!';
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={desc} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={desc} />
	<meta property="og:image" content={meta_img} />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={desc} />
	<meta name="twitter:image" content={meta_img} />
</svelte:head>

<AllBlocksTH />
