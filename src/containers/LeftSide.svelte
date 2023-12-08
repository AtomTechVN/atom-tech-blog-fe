<script>
    // import left side button list
    import RightSideMenuButton from "$components/button/RightSideMenuButton.svelte";
    import HomeIcon from "$icons/HomeIcon.svelte";
    import PodcastsIcon from "$icons/PodcastsIcon.svelte";
    import VideosIcon from "$icons/VideosIcon.svelte";
    import TagsIcon from "$icons/TagsIcon.svelte";
    import FAQIcon from "$icons/FAQIcon.svelte";
    import ForemShopIcon from "$icons/ForemShopIcon.svelte";
    import AdvertiseOnDEVIcon from "$icons/AdvertiseOnDEVIcon.svelte";
    import AboutIcon from "$icons/AboutIcon.svelte";
    import ContactIcon from "$icons/ContactIcon.svelte";
    import GuidesIcon from "$icons/GuidesIcon.svelte";
    import SoftwareComparisonsIcon from "$icons/SoftwareComparisonsIcon.svelte";

    // import left side button media
    import TwiterIcon from "$icons/TwiterIcon.svelte";

    // import other
    import SocialMediaButton from "$components/button/SocialMediaButton.svelte";
    
    const buttons = [
        {
            id:1,
            icon:HomeIcon,
            content:'Home',
            href:'#'
        },
        {
            id:2,
            icon:PodcastsIcon,
            content:'Podcasts',
            href:'#'
        },
        {
            id:3,
            icon:VideosIcon,
            content:'Videos',
            href:'#'
        },
        {
            id:4,
            icon:TagsIcon,
            content:'Tags',
            href:'#'
        },
        {
            id:5,
            icon:FAQIcon,
            content:'FAQ',
            href:'#'
        },
        {
            id:6,
            icon:ForemShopIcon,
            content:'Forem Shop',
            href:'#'
        },
        {
            id:7,
            icon:AdvertiseOnDEVIcon,
            content:'Advertise On DEV',
            href:'#'
        },
        {
            id:8,
            icon:AboutIcon,
            content:'About',
            href:'#'
        },
        {
            id:9,
            icon:ContactIcon,
            content:'Contact',
            href:'#'
        },
        {
            id:10,
            icon:GuidesIcon,
            content:'Guides',
            href:'#'
        },
        {
            id:11,
            icon:SoftwareComparisonsIcon,
            content:'Software Comparisons',
            href:'#'
        }

    ]

    const socialMedias = [
        {
            id: 1,
            icon:TwiterIcon,
            href:'#'
        }
    ]
</script>
<div class="flex flex-col">
    {#each buttons as button (button.id)}
        <RightSideMenuButton icon={button.icon}>{button.content}</RightSideMenuButton>
    {/each}
    <div>
        {#each socialMedias as socialMedia (socialMedia.id)}
            <SocialMediaButton href={socialMedia.href} icon={socialMedia.icon}/>
        {/each}
    </div>
</div>