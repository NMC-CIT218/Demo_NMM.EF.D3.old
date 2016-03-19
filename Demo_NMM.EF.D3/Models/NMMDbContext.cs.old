using System;
using System.Collections.Generic;
using System.Linq;
using System.Web;
using System.Data.Entity;
using Microsoft.AspNet.Identity.EntityFramework;

namespace Demo_NMM.EF.D2.Models
{
    public class NMMDbContext : IdentityDbContext<NMMUser>
    {
        public NMMDbContext()
            : base("NMMDb")
        {

        }

        public DbSet<Brewery> Breweries { get; set; }
        public DbSet<BreweryReview> BreweryReviews { get; set; }
        public DbSet<Beer> Beers { get; set; }
    }
}