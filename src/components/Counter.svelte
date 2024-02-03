<script>

import {number, incrementNumber, decrementNumber} from '../stores/main'

</script>

<button on:click={() => decrementNumber()}>-</button>
{$number}
<button on:click={() => incrementNumber()}>+</button>
