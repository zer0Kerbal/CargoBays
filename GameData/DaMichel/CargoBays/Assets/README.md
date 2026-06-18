```
# Normal fix
# bay_normals_NRM.dds.bak is the original
magick bay_normals_NRM.dds.bak -channel A -fx r -define dds:compression=dxt5 bay_normals_NRM.dds

# Base colors (alpha = 0% for matte finishes), from design files
# design_colormap_white.dds is the original colormap file
magick design_colormap_white.dds -alpha set -channel A -evaluate set 0% -define dds:compression=dxt5 bay_colormap_white.dds
magick design_colormap_light-grey.dds -alpha set -channel A -evaluate set 0% -define dds:compression=dxt5 bay_colormap_light-grey.dds
magick design_colormap_rough-grey.dds -alpha set -channel A -evaluate set 0% -define dds:compression=dxt5 bay_colormap_rough-grey.dds
magick design_colormap_grey.dds -alpha set -channel A -evaluate set 0% -define dds:compression=dxt5 bay_colormap_grey.dds
magick design_colormap_darker-grey.dds -alpha set -channel A -evaluate set 0% -define dds:compression=dxt5 bay_colormap_darker-grey.dds
magick design_colormap_dark-grey.dds -alpha set -channel A -evaluate set 0% -define dds:compression=dxt5 bay_colormap_dark-grey.dds

# Metallics
magick design_colormap_darker-grey.dds -alpha set -channel A -evaluate set 60% -define dds:compression=dxt5 bay_colormap_metallic.dds
magick design_colormap_darker-grey.dds -alpha set -channel A -evaluate set 99% -define dds:compression=dxt5 bay_colormap_polished-metallic.dds

```
