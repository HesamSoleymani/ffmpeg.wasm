import Grid from '@mui/material/Unstable_Grid2';
import MuiThemeProvider from "@site/src/components/common/MuiThemeProvider";
import ExampleCard from "@site/src/components/common/ExampleCard";

# Examples

You can find how to use ffmpeg.wasm with frameworks here. :smile:

:::caution
Do remember to run `npm run build` in the root of the repository before trying
any of the example.
:::

<MuiThemeProvider>
  <Grid container rowSpacing={1} columnSpacing={1}>
    <Grid xs={12} sm={6} md={6} lg={6} xl={4}>
      <ExampleCard
        img="/img/vanilla.png"
        title="Vanilla JavaScript"
        desc="Plain JavaScript"
        url="https://github.com/ffmpegwasm/ffmpeg.wasm/tree/main/apps/vanilla-app"
      />
    </Grid>
    <Grid xs={12} sm={6} md={6} lg={6} xl={4}>
      <ExampleCard
        img="/img/react-vite.png"
        title="React + Vite"
        desc="React with Vite (multithread version)"
        url="https://github.com/ffmpegwasm/ffmpeg.wasm/tree/main/apps/react-vite-app"
      />
    </Grid>
    <Grid xs={12} sm={6} md={6} lg={6} xl={4}>
      <ExampleCard
        img="/img/vue-vite.png"
        title="Vue + Vite"
        desc="Vue with Vite (multithread version)"
        url="https://github.com/ffmpegwasm/ffmpeg.wasm/tree/main/apps/vue-vite-app"
      />
    </Grid>
  </Grid>
</MuiThemeProvider>
