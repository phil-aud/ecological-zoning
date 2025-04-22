## Description
As climate change accelerates, nations are moving towards meeting their nationally determined contributions and reducing greenhouse gas (GHG)emissions. Reporting of this from the agriculture, forestry and other land use sector relies on data related to land use and management, climate and soil type. Where such data are unavailable, the Intergovernmental Panel on Climate Change (IPCC) provides a set of default factors, based on an extensive literature review of likely GHG emission factors and carbon stock changes disaggregated by the Food and Agriculture Organization’s global ecological zones. As understanding of global ecological zones under environmental change improves, it becomes necessary to reassess such ecological zoning approaches to enable reporting of GHG emissions to support nationally determined contributions and global change studies. Here we propose a globally consistent ecological zoning approach based on Holdridge life zones, which tackles certain limitations found in the existing guidance provided by the IPCC. A set of three global ecological zone maps based on Holdridge life zones were devised using increasing levels of aggregation, which could support sustainability studies of global environmental change, specifically climate change, and be used as a zoning approach by the IPCC. 
Time-series data (version 4.07) from the Climatic Research Unit (CRU) at the University of East Anglia were used with global elevation data from United States Geological Survey (USGS) Earth Resources Observation Science (EROS) Data Centre 200821, to provide monthly variations in climate over the period 1901–2022 on high-resolution (0.5° × 0.5°) grids, to produce a globally consistent HLZ map with different aggregation levels.
This repository contains the Tiff files of the three aggregation levels of the Holdridge Life Zones. To read the full methodology, please consult the paper or contact the author. 

## Image Descriptions
- HLZ map—level III: a disaggregated map based on the original HLZs that includes all latitudinal regions and altitudinal belts with 107 classes 
SLD interval data:


```var sld_intervals_levelI =
'<RasterSymbolizer>' +
  '<ColorMap type="intervals" extended="false">' +
    '<ColorMapEntry color="#C71D31" quantity="11" label="Tropical rainforest"/>' +
    '<ColorMapEntry color="#D64758" quantity="12" label="Tropical moist forest"/>' +
    '<ColorMapEntry color="#E37280" quantity="13" label="Tropical dry forest"/>' +
    '<ColorMapEntry color="#EEA0A9" quantity="14" label="Tropical shrubland"/>' +
    '<ColorMapEntry color="#F7CED3" quantity="15" label="Tropical desert"/>' + 
    '<ColorMapEntry color="#F17C1D" quantity="21" label="Subtropical rain forest"/>' +
    '<ColorMapEntry color="#F89646" quantity="22" label="Subtropical moist forest"/>' +
    '<ColorMapEntry color="#FDB071" quantity="23" label="Subtropical dry forest"/>' +
    '<ColorMapEntry color="#FFCA9E" quantity="24" label="Subtropical shrubland"/>' +
    '<ColorMapEntry color="#FFE4CE" quantity="25" label="Subtropical desert"/>' +
    '<ColorMapEntry color="#FFDD00" quantity="31" label="Temperate rain forest"/>' +
    '<ColorMapEntry color="#FFE833" quantity="32" label="Temperate moist forest"/>' +
    '<ColorMapEntry color="#FFF066" quantity="33" label="Temperate dry forest"/>' +
    '<ColorMapEntry color="#FFF799" quantity="34" label="Temperate shrubland"/>' +
    '<ColorMapEntry color="#FFFCCC" quantity="35" label="Temperate desert"/>' +
    '<ColorMapEntry color="#74A900" quantity="41" label="Cool Temperate rain/wet forest"/>' +
    '<ColorMapEntry color="#9BC444" quantity="42" label="Cool Temperate moist forst"/>' +
    '<ColorMapEntry color="#C0DC88" quantity="43" label="Cool Temperate steppe"/>' +
    '<ColorMapEntry color="#E5F1CC" quantity="44" label="Cool Temperate desert"/>' +
    '<ColorMapEntry color="#009F49" quantity="51" label="Boreal rain/wet forest"/>' +
    '<ColorMapEntry color="#44BD79" quantity="52" label="Boreal moist forest"/>' +
    '<ColorMapEntry color="#88D7AA" quantity="53" label="Boreal dry scrub"/>' +
    '<ColorMapEntry color="#CCEFDA" quantity="54" label="Boreal desert"/>' +
    '<ColorMapEntry color="#0088D6" quantity="61" label="Subpolar rain/wet tundra"/>' +
    '<ColorMapEntry color="#66B9ED" quantity="62" label="Subpolar moist tundra"/>' +
    '<ColorMapEntry color="#CCE8FB" quantity="63" label="Subpolar dry tundra"/>' +
    '<ColorMapEntry color="#1451a0" quantity="71" label="Polar"/>' +
  '</ColorMap>' +
'</RasterSymbolizer>';
```

- HLZ map—level II: aggregated along latitudinal regions and where altitudinal belts become latitudinal equivalents with 38 classes 

```var sld_intervals_levelII =
'<RasterSymbolizer>' +
  '<ColorMap type="intervals" extended="false">' +
    '<ColorMapEntry color="#ce1d09" quantity="111" label="Tropical Rain Forest"/>' +
    '<ColorMapEntry color="#ce1d09" quantity="112" label="Tropical Wet Forest"/>' +
    '<ColorMapEntry color="#D53B2A" quantity="113" label="Tropical Moist Forest"/>' +
    '<ColorMapEntry color="#DB594B" quantity="114" label="Tropical Dry Forest"/>' +
    '<ColorMapEntry color="#E2776B" quantity="115" label="Tropical Very Dry Forest"/>' +
    '<ColorMapEntry color="#E8968C" quantity="116" label="Tropical Thorn Woodland"/>' +
    '<ColorMapEntry color="#EFB4AD" quantity="117" label="Tropical Desert Scrub"/>' +
    '<ColorMapEntry color="#F5D2CE" quantity="118" label="Tropical Desert"/>' +
    '<ColorMapEntry color="#f19137" quantity="121" label="Tropical Premontane Rain Forest"/>' +
    '<ColorMapEntry color="#F3A052" quantity="122" label="Tropical Premontane Wet Forest"/>' +
    '<ColorMapEntry color="#F5AE6C" quantity="123" label="Tropical Premontane Moist Forest"/>' +
    '<ColorMapEntry color="#F7BD87" quantity="124" label="Tropical Premontane Dry Forest"/>' +
    '<ColorMapEntry color="#F9CCA2" quantity="125" label="Tropical Premontane Thorn Woodland"/>' +
    '<ColorMapEntry color="#FADABC" quantity="126" label="Tropical Premontane Desert Scrub"/>' +
    '<ColorMapEntry color="#FCE9D7" quantity="127" label="Tropical Premontane Desert"/>' +
    '<ColorMapEntry color="#ffde4a" quantity="131" label="Tropical Lower Montane Rain Forest"/>' +
    '<ColorMapEntry color="#FFE262" quantity="132" label="Tropical Lower Montane Wet Forest"/>' +
    '<ColorMapEntry color="#FFE77A" quantity="133" label="Tropical Lower Montane Moist Forest"/>' +
    '<ColorMapEntry color="#FFEB92" quantity="134" label="Tropical Lower Montane Dry Forest"/>' +
    '<ColorMapEntry color="#FFF0AB" quantity="135" label="Tropical Lower Montane Thorn Woodland"/>' +
    '<ColorMapEntry color="#FFF4C3" quantity="136" label="Tropical Lower Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#FFF8DB" quantity="137" label="Tropical Lower Montane Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="141" label="Tropical Montane Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="142" label="Tropical Montane Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="143" label="Tropical Montane Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="144" label="Tropical Montane Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="145" label="Tropical Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="146" label="Tropical Montane Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="151" label="Tropical Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="152" label="Tropical Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="153" label="Tropical Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="154" label="Tropical Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="155" label="Tropical Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="161" label="Tropical Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="162" label="Tropical Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="163" label="Tropical Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="164" label="Tropical Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="171" label="Tropical Nival Desert"/>' +
    '<ColorMapEntry color="#f19137" quantity="211" label="Subtropical Rain Forest"/>' +
    '<ColorMapEntry color="#F3A052" quantity="212" label="Subtropical Wet Forest"/>' +
    '<ColorMapEntry color="#F5AE6C" quantity="213" label="Subtropical Moist Forest"/>' +
    '<ColorMapEntry color="#F7BD87" quantity="214" label="Subtropical Dry Forest"/>' +
    '<ColorMapEntry color="#F9CCA2" quantity="215" label="Subtropical Thorn Woodland"/>' +
    '<ColorMapEntry color="#FADABC" quantity="216" label="Subtropical Desert Scrub"/>' +
    '<ColorMapEntry color="#FCE9D7" quantity="217" label="Subtropical Desert"/>' +
    '<ColorMapEntry color="#ffde4a" quantity="221" label="Subtropical Lower Montane Rain Forest"/>' +
    '<ColorMapEntry color="#FFE262" quantity="222" label="Subtropical Lower Montane Wet Forest"/>' +
    '<ColorMapEntry color="#FFE77A" quantity="223" label="Subtropical Lower Montane Moist Forest"/>' +
    '<ColorMapEntry color="#FFEB92" quantity="224" label="Subtropical Lower Montane Dry Forest"/>' +
    '<ColorMapEntry color="#FFF0AB" quantity="225" label="Subtropical Lower Montane Thorn Woodland"/>' +
    '<ColorMapEntry color="#FFF4C3" quantity="226" label="Subtropical Lower Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#FFF8DB" quantity="227" label="Subtropical Lower Montane Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="231" label="Subtropical Montane Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="232" label="Subtropical Montane Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="233" label="Subtropical Montane Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="234" label="Subtropical Montane Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="235" label="Subtropical Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="236" label="Subtropical Montane Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="241" label="Subtropical Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="242" label="Subtropical Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="243" label="Subtropical Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="244" label="Subtropical Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="245" label="Subtropical Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="251" label="Subtropical Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="252" label="Subtropical Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="253" label="Subtropical Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="254" label="Subtropical Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="261" label="Subtropical Nival Desert"/>' +
    '<ColorMapEntry color="#ffde4a" quantity="311" label="Warm Temperate Rain Forest"/>' +
    '<ColorMapEntry color="#FFE262" quantity="312" label="Warm Temperate Wet Forest"/>' +
    '<ColorMapEntry color="#FFE77A" quantity="313" label="Warm Temperate Moist Forest"/>' +
    '<ColorMapEntry color="#FFEB92" quantity="314" label="Warm Temperate Dry Forest"/>' +
    '<ColorMapEntry color="#FFF0AB" quantity="315" label="Warm Temperate Thorn Woodland"/>' +
    '<ColorMapEntry color="#FFF4C3" quantity="316" label="Warm Temperate Desert Scrub"/>' +
    '<ColorMapEntry color="#FFF8DB" quantity="317" label="Warm Temperate Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="321" label="Warm Temperate Montane Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="322" label="Warm Temperate Montane Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="323" label="Warm Temperate Montane Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="324" label="Warm Temperate Montane Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="325" label="Warm Temperate Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="326" label="Warm Temperate Montane Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="331" label="Warm Temperate Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="332" label="Warm Temperate Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="333" label="Warm Temperate Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="334" label="Warm Temperate Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="335" label="Warm Temperate Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="341" label="Warm Temperate Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="342" label="Warm Temperate Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="343" label="Warm Temperate Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="344" label="Warm Temperate Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="351" label="Warm Temperate Nival Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="411" label="Cool Temperate Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="412" label="Cool Temperate Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="413" label="Cool Temperate Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="414" label="Cool Temperate Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="415" label="Cool Temperate Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="416" label="Cool Temperate Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="421" label="Cool Temperate Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="422" label="Cool Temperate Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="423" label="Cool Temperate Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="424" label="Cool Temperate Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="425" label="Cool Temperate Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="431" label="Cool Temperate Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="432" label="Cool Temperate Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="433" label="Cool Temperate Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="434" label="Cool Temperate Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="441" label="Cool Temperate Nival Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="511" label="Boreal Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="512" label="Boreal Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="513" label="Boreal Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="514" label="Boreal Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="515" label="Boreal Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="521" label="Boreal Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="522" label="Boreal Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="523" label="Boreal Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="524" label="Boreal Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="531" label="Boreal Nival Desert"/>' +
    '<ColorMapEntry color="#00add6" quantity="611" label="Subpolar Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="612" label="Subpolar Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="613" label="Subpolar Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="614" label="Subpolar Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="621" label="Subpolar Nival Desert"/>' +
    '<ColorMapEntry color="#1451a0" quantity="711" label="Polar"/>' +
  '</ColorMap>' +
'</RasterSymbolizer>';
```
- HLZ map—level I: a fully aggregated HLZ map that is a further simplification of Holdridge’s life zone map to achieve classes similar to GEZ 2010 that could be useful to the IPCC.

```var sld_intervals_levelIII =
'<RasterSymbolizer>' +
  '<ColorMap type="intervals" extended="false">' +
    '<ColorMapEntry color="#ce1d09" quantity="111" label="Tropical Rain Forest"/>' +
    '<ColorMapEntry color="#ce1d09" quantity="112" label="Tropical Wet Forest"/>' +
    '<ColorMapEntry color="#D53B2A" quantity="113" label="Tropical Moist Forest"/>' +
    '<ColorMapEntry color="#DB594B" quantity="114" label="Tropical Dry Forest"/>' +
    '<ColorMapEntry color="#E2776B" quantity="115" label="Tropical Very Dry Forest"/>' +
    '<ColorMapEntry color="#E8968C" quantity="116" label="Tropical Thorn Woodland"/>' +
    '<ColorMapEntry color="#EFB4AD" quantity="117" label="Tropical Desert Scrub"/>' +
    '<ColorMapEntry color="#F5D2CE" quantity="118" label="Tropical Desert"/>' +
    '<ColorMapEntry color="#f19137" quantity="121" label="Tropical Premontane Rain Forest"/>' +
    '<ColorMapEntry color="#F3A052" quantity="122" label="Tropical Premontane Wet Forest"/>' +
    '<ColorMapEntry color="#F5AE6C" quantity="123" label="Tropical Premontane Moist Forest"/>' +
    '<ColorMapEntry color="#F7BD87" quantity="124" label="Tropical Premontane Dry Forest"/>' +
    '<ColorMapEntry color="#F9CCA2" quantity="125" label="Tropical Premontane Thorn Woodland"/>' +
    '<ColorMapEntry color="#FADABC" quantity="126" label="Tropical Premontane Desert Scrub"/>' +
    '<ColorMapEntry color="#FCE9D7" quantity="127" label="Tropical Premontane Desert"/>' +
    '<ColorMapEntry color="#ffde4a" quantity="131" label="Tropical Lower Montane Rain Forest"/>' +
    '<ColorMapEntry color="#FFE262" quantity="132" label="Tropical Lower Montane Wet Forest"/>' +
    '<ColorMapEntry color="#FFE77A" quantity="133" label="Tropical Lower Montane Moist Forest"/>' +
    '<ColorMapEntry color="#FFEB92" quantity="134" label="Tropical Lower Montane Dry Forest"/>' +
    '<ColorMapEntry color="#FFF0AB" quantity="135" label="Tropical Lower Montane Thorn Woodland"/>' +
    '<ColorMapEntry color="#FFF4C3" quantity="136" label="Tropical Lower Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#FFF8DB" quantity="137" label="Tropical Lower Montane Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="141" label="Tropical Montane Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="142" label="Tropical Montane Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="143" label="Tropical Montane Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="144" label="Tropical Montane Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="145" label="Tropical Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="146" label="Tropical Montane Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="151" label="Tropical Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="152" label="Tropical Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="153" label="Tropical Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="154" label="Tropical Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="155" label="Tropical Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="161" label="Tropical Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="162" label="Tropical Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="163" label="Tropical Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="164" label="Tropical Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="171" label="Tropical Nival Desert"/>' +
    '<ColorMapEntry color="#f19137" quantity="211" label="Subtropical Rain Forest"/>' +
    '<ColorMapEntry color="#F3A052" quantity="212" label="Subtropical Wet Forest"/>' +
    '<ColorMapEntry color="#F5AE6C" quantity="213" label="Subtropical Moist Forest"/>' +
    '<ColorMapEntry color="#F7BD87" quantity="214" label="Subtropical Dry Forest"/>' +
    '<ColorMapEntry color="#F9CCA2" quantity="215" label="Subtropical Thorn Woodland"/>' +
    '<ColorMapEntry color="#FADABC" quantity="216" label="Subtropical Desert Scrub"/>' +
    '<ColorMapEntry color="#FCE9D7" quantity="217" label="Subtropical Desert"/>' +
    '<ColorMapEntry color="#ffde4a" quantity="221" label="Subtropical Lower Montane Rain Forest"/>' +
    '<ColorMapEntry color="#FFE262" quantity="222" label="Subtropical Lower Montane Wet Forest"/>' +
    '<ColorMapEntry color="#FFE77A" quantity="223" label="Subtropical Lower Montane Moist Forest"/>' +
    '<ColorMapEntry color="#FFEB92" quantity="224" label="Subtropical Lower Montane Dry Forest"/>' +
    '<ColorMapEntry color="#FFF0AB" quantity="225" label="Subtropical Lower Montane Thorn Woodland"/>' +
    '<ColorMapEntry color="#FFF4C3" quantity="226" label="Subtropical Lower Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#FFF8DB" quantity="227" label="Subtropical Lower Montane Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="231" label="Subtropical Montane Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="232" label="Subtropical Montane Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="233" label="Subtropical Montane Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="234" label="Subtropical Montane Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="235" label="Subtropical Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="236" label="Subtropical Montane Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="241" label="Subtropical Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="242" label="Subtropical Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="243" label="Subtropical Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="244" label="Subtropical Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="245" label="Subtropical Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="251" label="Subtropical Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="252" label="Subtropical Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="253" label="Subtropical Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="254" label="Subtropical Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="261" label="Subtropical Nival Desert"/>' +
    '<ColorMapEntry color="#ffde4a" quantity="311" label="Warm Temperate Rain Forest"/>' +
    '<ColorMapEntry color="#FFE262" quantity="312" label="Warm Temperate Wet Forest"/>' +
    '<ColorMapEntry color="#FFE77A" quantity="313" label="Warm Temperate Moist Forest"/>' +
    '<ColorMapEntry color="#FFEB92" quantity="314" label="Warm Temperate Dry Forest"/>' +
    '<ColorMapEntry color="#FFF0AB" quantity="315" label="Warm Temperate Thorn Woodland"/>' +
    '<ColorMapEntry color="#FFF4C3" quantity="316" label="Warm Temperate Desert Scrub"/>' +
    '<ColorMapEntry color="#FFF8DB" quantity="317" label="Warm Temperate Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="321" label="Warm Temperate Montane Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="322" label="Warm Temperate Montane Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="323" label="Warm Temperate Montane Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="324" label="Warm Temperate Montane Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="325" label="Warm Temperate Montane Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="326" label="Warm Temperate Montane Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="331" label="Warm Temperate Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="332" label="Warm Temperate Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="333" label="Warm Temperate Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="334" label="Warm Temperate Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="335" label="Warm Temperate Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="341" label="Warm Temperate Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="342" label="Warm Temperate Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="343" label="Warm Temperate Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="344" label="Warm Temperate Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="351" label="Warm Temperate Nival Desert"/>' +
    '<ColorMapEntry color="#9ec200" quantity="411" label="Cool Temperate Rain Forest"/>' +
    '<ColorMapEntry color="#AECC29" quantity="412" label="Cool Temperate Wet Forest"/>' +
    '<ColorMapEntry color="#BDD652" quantity="413" label="Cool Temperate Moist Forest"/>' +
    '<ColorMapEntry color="#CDDF7A" quantity="414" label="Cool Temperate Steppe"/>' +
    '<ColorMapEntry color="#DCE9A3" quantity="415" label="Cool Temperate Desert Scrub"/>' +
    '<ColorMapEntry color="#ECF3CC" quantity="416" label="Cool Temperate Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="421" label="Cool Temperate Subalpine Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="422" label="Cool Temperate Subalpine Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="423" label="Cool Temperate Subalpine Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="424" label="Cool Temperate Subalpine Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="425" label="Cool Temperate Subalpine Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="431" label="Cool Temperate Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="432" label="Cool Temperate Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="433" label="Cool Temperate Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="434" label="Cool Temperate Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="441" label="Cool Temperate Nival Desert"/>' +
    '<ColorMapEntry color="#009837" quantity="511" label="Boreal Rain Forest"/>' +
    '<ColorMapEntry color="#33AD5F" quantity="512" label="Boreal Wet Forest"/>' +
    '<ColorMapEntry color="#66C187" quantity="513" label="Boreal Moist Forest"/>' +
    '<ColorMapEntry color="#99D6AF" quantity="514" label="Boreal Dry Scrub"/>' +
    '<ColorMapEntry color="#CCEAD7" quantity="515" label="Boreal Desert"/>'+
    '<ColorMapEntry color="#00add6" quantity="521" label="Boreal Alpine Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="522" label="Boreal Alpine Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="523" label="Boreal Alpine Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="524" label="Boreal Alpine Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="531" label="Boreal Nival Desert"/>' +
    '<ColorMapEntry color="#00add6" quantity="611" label="Subpolar Rain Tundra"/>' +
    '<ColorMapEntry color="#44C3E1" quantity="612" label="Subpolar Wet Tundra"/>' +
    '<ColorMapEntry color="#88D9EC" quantity="613" label="Subpolar Moist Tundra"/>' +
    '<ColorMapEntry color="#CCEFF7" quantity="614" label="Subpolar Desert"/>'+
    '<ColorMapEntry color="#1451a0" quantity="621" label="Subpolar Nival Desert"/>' +
    '<ColorMapEntry color="#1451a0" quantity="711" label="Polar"/>' +
  '</ColorMap>' +
'</RasterSymbolizer>';
```
## Source
Audebert, P., Milne, E., Schiettecatte, LS. et al. Ecological zoning for climate policy and global change studies. Nat Sustain 7, 1294–1303 (2024). https://doi.org/10.1038/s41893-024-01416-5

## Metadata
- File Format: GeoTIFF (.tif)
- Projection: EPSG:4326 
- Resolution: 1,000m 
- Export Region: Global
- Date: 29 August 2024

## Contact
Author: Philip Audebert, Food and Agriculture Organization of the United Nations, Philip.audebert@sciencespo.fr
