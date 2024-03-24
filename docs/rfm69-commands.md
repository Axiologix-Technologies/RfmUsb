# Rfm Usb Command List

CLI Command | Description
---------|----------
help|Lists all the registered commands
g-ts|Get FreeRTOS tasks
g-hs|Get heap stats
e-r|Reset RfmUsb
g-fv|Get firmware version
g-ob|Get output base
s-ob|Set output base: 0-1
s-co|Set cli output: 0-1
g-msn|Get mcu serial number
g-rv|Get register value. 0-0xFF
s-rv|Set register value. 0-0xFF 0-0xFF
e-tx|Execute tx: hex(1-66) [tx count: 1 - 20] [tx interval: 10 - 1000] [timeout: 10 - 5000]
e-bl|Enter bootloader
g-lrssi|Get last packet rssi
g-fifo|Read the fifo
s-fifo|Write the fifo: hex (1-66)
g-dim|Get dio interrupt mask
s-dim|Set dio interrupt mask: 0-0x3F
g-dio|Get dio mapping: 0-5
s-dio|Set dio mapping: 0-5 0-3
g-so|Get sequencer off
s-so|Set sequencer off: 0-1
g-lo|Get listen on
s-lo|Set listen on: 0-1
e-lma|Execute listen mode abort. Mode: 0-5
g-om|Get operating mode
s-om|Set operating mode: 0-5
g-dm|Get data mode
s-dm|Set data mode: 0-3
g-mt|Get modulation type
s-mt|Set modulation type: 0-1
g-fs|Get fsk shaping
s-fs|Set fsk shaping: 0-4
g-os|Get ook shaping
s-os|Set ook shaping: 0-2
g-br|Get bit rate
s-br|Set bit rate: 1200-300000
g-fd|Get freq deviation
s-fd|Set freq deviation: 0-0x3FFF
g-f|Get frequency
s-f|Set frequency: 0-102E+7
e-rc|Calibrate rc oscillator
g-ab|Get afc beta
s-ab|Set afc beta: 0-1
g-ir|Get idle resolution
s-ir|Set idle resolution: 0-3
g-rr|Get rx resolution
s-rr|Set rx resolution: 0-3
g-lc|Get listen criteria
s-lc|Set listen criteria: 0-1
g-lem|Get listen end mode
s-lem|Set listen end mode: 0-2
g-lic|Get listen idle coefficient
s-lic|Set listen idle coefficient: 0-255
g-lrc|Get listen rx coefficient
s-lrc|Set listen rx coefficient: 0-255
g-v|Get radio version
g-op|Get output power level dBm
s-op|Set output power level dBm: -2 - 20
g-par|Get power amp ramp times
s-par|Set power amp ramp times: 0-15
g-ocp|Get ocp
s-ocp|Set ocp: 0-1
g-ocpt|Get ocp trim
s-ocpt|Set ocp trim: 0-15
g-lnaz|Get Lna Impedance
s-lnaz|Set lna impedance: 0-1
g-lnag|Get lna gain
g-lnags|Get lna gain select
s-lnags|Set lna gain select: 0-7
g-df|Get dcc frequency
s-df|Set dcc frequency: 0-7
g-dfa|Get dcc freq for afc
s-dfa|Set dcc freq for afc: 0-7
g-ott|Get ook threshold type
s-ott|Set ook threshold type: 0-3
g-opts|Get ook peak threshold step
s-opts|Set ook peak threshold step: 0-7
g-optd|Get ook peak threshold decrement
s-optd|Set ook peak threshold decrement: 0-7
g-oatf|Get ook average threshold filter
s-oatf|Set ook average threshold filter: 0-3
g-oft|Get ook fixed threshold
s-oft|Set ook fixed threshold: 0-255
e-fei|Executes a fei measurement
g-aac|Get afc auto clear
s-aac|Set afc auto clear: 0-1
g-aao|Get afc auto on
s-aao|Set afc auto on: 0-1
e-ac|Execute afc clear
e-a|Executes afc
e-ac|Clear afc value
g-afc|Get afc value
g-fei|Get fei value
e-rssi|Execute rssi measurement
g-r|Get rssi value
s-rxbw|Set rx channel filter bandwidth: 0-23
g-rxbw|Get rx channel filter bandwidth
s-rxbwa|Set rx channel filter bandwidth for afc: 0-23
g-rxbwa|Get rx channel filter bandwidth for afc
g-rt|Get rssi threshold
s-rt|Set rssi threshold: -115 - 0
g-trs|Get timeout rx start
s-trs|Set timeout rx start: 0-255
g-trt|Get timeout rssi threshold
s-trt|Get timeout rssi threshold: 0-255
g-irq|Get irq flags
s-irq|Set irq flags. 010-0x0910
g-ps|Get preamble size
s-ps|Set preamble size: 0-65535
g-se|Get sync enable
s-se|Set sync enable: 0-1
g-ffc|Get fifo fill condition
s-ffc|Set fifo fill condition: 0-1
g-ss|Get sync size
s-ss|Set sync size: 0-7
g-sbe|Get sync bit errors
s-sbe|Set sync bit errors: 0-7
g-sync|Get sync bytes
s-sync|Set sync bytes: hex (1-8)
g-pf|Get packet format
s-pf|Set packet format: 0-1
g-dfe|Get dc free encoding
s-dfe|Set dc free encoding: 0-3
g-crc|Get crc check on
s-crc|Set crc check on: 0-1
g-caco|Get crc auto clear off
s-caco|Set crc auto clear off: 0-1
g-af|Get address filter
s-af|Set address filter: 0-3
g-pl|Get packet length
s-pl|Set packet length: 0-255
g-na|Get node address
s-na|Set node address: 0-255
g-ba|Get broadcast address
s-ba|Set broadcast address: 0-255
g-amec|Get auto mode enter condition
s-amec|Set auto mode enter condition: 0-7
g-amexc|Get auto mode exit condition
s-amexc|Set auto mode exit condition: 0-7
g-im|Get intermediate mode
s-im|Set intermediate mode: 0-3
g-tsc|Get tx start condition
s-tsc|Get tx start condition: 0-1
g-ft|Get fifo threshold
s-ft|Set fifo threshold: 0-127
g-iprd|Get inter packet rx delay
s-iprd|Set inter packet rx delay: 0-15
e-rr|Execute restarts rx
g-arre|Get auto rx restart enable
s-arre|Set auto rx restart enable: 0-1
s-aes|Set aes key: hex(1-16)
g-ae|Get aes enabled
s-ae|Set aes enabled: 0-1
e-tm|Execute temperature measurement
g-t|Get temperature value
g-sb|Get sensitivity boost
s-sb|Set sensitivity boost: 0-1
g-cd|Get continuous dagc
s-cd|Set continuous dagc: 0-2
g-lbao|Get low beta afc offset
s-lbao|Set low beta afc offset: 0-1
g-be|Get io buffer read enable
s-be|Set io buffer read enable
g-bi|Get io buffer info
r-b|Read io buffer: [count: 1-256]
w-b|Write io buffer: hex (1-64)
e-btx|Execute io buffer transmit
