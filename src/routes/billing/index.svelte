<script>
    import { goto } from '$app/navigation';
</script>
<svelte:head>Billing Home</svelte:head>
<div>
    <h2>Outstanding - Not Billed</h2>
    <p>$1,500</p>
    <button>Invoice all Outstanding</button>
    <h2>Outstanding - Billed</h2>
    <p>$500</p>
    <button>Record Payments</button>
</div>
<div>
    <h3>Recent Invoices</h3>
    <table>
        <tr>
            <th>Customer</th>
            <th>Amount</th>
            <th>Invoice</th>
            <th>Actions</th>
        </tr>
        <tr>
            <td>
                Jim's Landscaping Inc.
            </td>
            <td>
                $109
            </td>
            <td>
                Doc
            </td>
            <td>
                <a href="/billing/invoice/new">New Invoice</a>
                <a href="/">Record Payment</a>
                <a href="/customer/2">Go to Customer</a>
            </td>
        </tr>
    </table>
</div>