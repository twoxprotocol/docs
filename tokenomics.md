import Bleed from 'nextra-theme-docs/bleed'
import Callout from 'nextra-theme-docs/callout'
import { Chart } from "react-google-charts";


Following describes $TWOX token supply allocation 

##Tokenomics

<Bleed>
  <Chart
    chartType="PieChart"
    data={[
      [ "Receivers", "Amount" ],
      [ "Sale", 15.60 ],
      [ "Team", 9 ],
      [ "Venture Round", 16.40 ],
      [ "Community", 11.2 ],
      [ "Treasury", 47.80 ]
    ]}
    options={{
      title: "Tokenomics",
      backgroundColor: '#ffffff',
      colors: ['#79F8DB', '#FDBF40', '#027FFF', '#FF1301', '#FBBF42', '#F1EBE2', '#EDE7DB'],
      legend: {textStyle: {color: 'black'}},
      pieHole: 0.6,
      titleTextStyle: { color: 'black' },
    }}
    width={"100%"}
    height={"600px"}
  />
</Bleed>
